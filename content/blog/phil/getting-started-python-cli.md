---
title: "Getting Started with the Python CLI"
description: "<script type=text/javascript>toc_collapse=0;</script><div class=toc id=toc>\n<div class=toc-title>Table of conte"
date: "2013-10-31"
author: "phil"
tags:
    - "blog"
---

<script type="text/javascript">toc_collapse=0;</script><div class="toc" id="toc">
<div class="toc-title">Table of contents<span class="toc-toggle-message">&nbsp;</span></div>
<div class="toc-list">
<ol>
<li class="toc-level-1"><a href="#Setup">Setup</a>
<ol>
<li class="toc-level-2"><a href="#Install">Install</a></li>
<li class="toc-level-2"><a href="#Configure">Configure</a></li>
</ol>
</li>
<li class="toc-level-1"><a href="#Help">Help</a></li>
<li class="toc-level-1"><a href="#Filters">Filters</a></li>
<li class="toc-level-1"><a href="#Examples">Examples</a>
<ol>
<li class="toc-level-2"><a href="#CCI">CCI</a></li>
<li class="toc-level-2"><a href="#DNS">DNS</a></li>
</ol>
</li>
</ol>
</div>
</div>
<p>The SoftLayer API client includes a utility, <span class="geshifilter"><code class="text geshifilter-text">sl</code></span>, that provides a way to manage portions of a SoftLayer environment on the command line. Each section of the CLI shares a name with a manager that powers it. These managers wrap the necessary SoftLayer API calls and allow the CLI libraries to focus on data manipulation and display.</p>
<h2 id="Setup">Setup</h2>
<h3 id="Install">Install</h3>
<p>The SLAPI CLI tool is included with the SoftLayer Python API Client. To install please follow <a href="https://softlayer-api-python-client.readthedocs.org/en/latest/install/">these steps</a></p>
<h3 id="Configure">Configure</h3>
<p>The easiest way to get going it to use the automated configuration tool built into the CLI. This can be accessed with the arguments <span class="geshifilter"><code class="text geshifilter-text">config setup</code></span>. The configuration tool will prompt for your SoftLayer Portal username, API Key and Endpoint URL of choice. The default endpoint will be fine for most use cases.</p>
<p>If you do not already have an API key, your portal username can be used and the CLI will generate and populate your config with the a API key.</p>
<p>However you can also create/obtain an API key by following <a href="http://knowledgelayer.softlayer.com/procedure/retrieve-your-api-key">this guide</a></p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl config setup
Username []: foo
API Key or Password []: bar
Endpoint (public|private|custom): public
:..............:..................................................................:
:         Name : Value                                                            :
:..............:..................................................................:
:     Username : foo                                                              :
:      API Key : bar                                                              :
: Endpoint URL : https://api.softlayer.com/xmlrpc/v3/                             :
:      Timeout : not set                                                          :
:..............:..................................................................:
Are you sure you want to write settings to "/Users/foo/.softlayer"? [Y/n]: y
Configuration Updated Successfully</pre></div>
<p>These values can also be manually added to the <a href="https://softlayer-api-python-client.readthedocs.org/en/latest/config_file/#config-file">configuration file manually</a></p>
<h2 id="Help">Help</h2>
<p>A comprehensive help dialogue is available for all CLI features. A general help menu can be accessed with the <span class="geshifilter"><code class="text geshifilter-text">-h</code></span> flag. Typically this flag can also be added to the end of any command to obtain additional information.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl -h
usage: sl <module> [<args>...]
       sl help <module>
       sl help <module> <command>
       sl [-h | --help]
&nbsp;
SoftLayer Command-line Client
&nbsp;
The available modules are:
&nbsp;
Compute:
  bmc       Bare Metal Cloud
  cci       Cloud Compute Instances
  image     Manages compute and flex images
  metadata  Get details about this machine. Also available with 'my' and 'meta'
  server    Hardware servers
  sshkey    Manage SSH keys on your account
&nbsp;
Networking:
  dns       Domain Name System
  firewall  Firewall rule and security management
  globalip  Global IP address management
  rwhois    RWhoIs operations
  ssl       Manages SSL
  subnet    Subnet ordering and management
  vlan      Manage VLANs on your account
&nbsp;
Storage:
  iscsi     View iSCSI details
  nas       View NAS details
&nbsp;
General:
  config    View and edit configuration for this tool
  summary   Display an overall summary of your account
  help      Show help</pre></div>
<p>Additional documentation for any specific command or module can be found with <span class="geshifilter"><code class="text geshifilter-text">sl <module> [<command>] -h</code></span></p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci list -h
usage: sl cci list [--hourly | --monthly] [--sortby=SORT_COLUMN] [--tags=TAGS]
                   [options]
&nbsp;
List CCIs
&nbsp;
Examples:
    sl cci list --datacenter=dal05
    sl cci list --network=100 --cpu=2
    sl cci list --memory='>= 2048'
    sl cci list --tags=production,db
&nbsp;
Options:
  --sortby=ARG  Column to sort by. options: id, datacenter, host,
                Cores, memory, primary_ip, backend_ip
&nbsp;
Filters:
  -c --cpu=CPU             Number of CPU cores
  -D --domain=DOMAIN       Domain portion of the FQDN. example: example.com
  -d DC, --datacenter=DC   datacenter shortname (sng01, dal05, ...)
  -H --hostname=HOST       Host portion of the FQDN. example: server
  -m --memory=MEMORY       Memory in mebibytes
  -n MBPS, --network=MBPS  Network port speed in Mbps
  --hourly                 Show hourly instances
  --monthly                Show monthly instances
  --tags=ARG               Only show instances that have one of these tags.
                             Comma-separated. (production,db)
&nbsp;
For more on filters see 'sl help filters'
&nbsp;
Standard Options:
  --format=ARG           Output format. [Options: table, raw] [Default: table]
  -C FILE --config=FILE  Config file location. [Default: ~/.softlayer]
  --debug=LEVEL          Specifies the debug noise level
                           1=warn, 2=info, 3=debug
  --timings              Time each API call and display after results
  -h --help              Show this screen</pre></div>
<h2 id="Filters">Filters</h2>
<p>Filters can be used to limit the number of responses from commands that accept them as arguments. You can access the filter help entry with <span class="geshifilter"><code class="text geshifilter-text">sl help filters</code></span>.</p>
<p>For example a list of all CCIs on an account has "webserver" in the hostname could be found with:</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci list --hostname='*webserver*'</pre></div>
<p>In most cases you can even apply multiple filters:</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci list --network='< 100' --cpu 2</pre></div>
<h2 id="Examples">Examples</h2>
<h3 id="CCI">CCI</h3>
<h4 id="Create">Create</h4>
<h5 id="Retrieve_options">Retrieve options</h5>
<p>A listing of values for cci create variables can be obtained with <span class="geshifilter"><code class="text geshifilter-text">sl cci create-options</code></span>. These values will populate your order with the proper information.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci create-options
:.................:....................................................................................................:
:            Name : Value                                                                                              :
:.................:....................................................................................................:
:      datacenter : ams01,dal05,sea01,sjc01,sng01,wdc01                                                                :
:  cpus (private) : 1,2,4,8                                                                                            :
: cpus (standard) : 1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16                                                             :
:          memory : 1024,2048,3072,4096,5120,6144,7168,8192,9216,10240,11264,12288,13312,14336,15360,16384,32768,49152 :
:     os (CENTOS) : CENTOS_5_32                                                                                        :
:                 : CENTOS_5_64                                                                                        :
:                 : CENTOS_6_32
...</pre></div>
<h5 id="Creating_the_CCI">Creating the CCI</h5>
<p>After the appropriate values have been chosen you can create a CCI with <span class="geshifilter"><code class="text geshifilter-text">sl cci create <options></code></span>:</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci create --hostname=foo-webserver --domain=example.com --cpu=1 --memory=1024 --hourly --os=DEBIAN_7_64
This action will incur charges on your account. Continue? [y/N]: y
:.........:......................................:
:    name : value                                :
:.........:......................................:
:      id : 1234212                              :
: created : 2013-09-30T06:51:02-06:00            :
:    guid : 093nt23n-90nl-9n2i-u902-902n3t09n23t :
:.........:......................................:</pre></div>
<p>The CLI will either respond as it has above with the details of your new instance, or it will provide an error message explaining what went wrong.</p>
<h4 id="Cancel">Cancel</h4>
<p>The cancellation command in the CCI argument will deprovision a CCI and remove its billing from you account. Cancellation is a destructive action - back up all data you wish to retain before running this command, as we do not keep records of information stored on your device.. Cancellation of an instance will result in the immediate destruction of the target CCI.</p>
<p>When using the <span class="geshifilter"><code class="text geshifilter-text">cancel</code></span> command you will be prompted to enter the CCI ID to start the cancellation process.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci cancel pjackson-cli-test
This action cannot be undone! Type "341234" or press Enter to abort: 341234</pre></div>
<h4 id="Reboot">Reboot</h4>
<p>Reboot a CCI with the <span class="geshifilter"><code class="text geshifilter-text">sl cci reboot</code></span> command. YoYou will be prompted to confirm the reboot before it begins. By default a soft reboot is attempted with the <span class="geshifilter"><code class="text geshifilter-text">--soft</code></span> option which will gracefully restart the device. If unable to complete a soft reboot, the <span class="geshifilter"><code class="text geshifilter-text">--hard</code></span> switch can be passed which will simulate a power cycling of the device.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci reboot foo-webserver
This will reboot the CCI with id 1234212. Continue? [y/N]: y</pre></div>
<h4 id="Search">Search</h4>
<p>Retrieve a list of all CCIs on your account can be retrieved with <span class="geshifilter"><code class="text geshifilter-text">sl cci list</code></span>. Filter your results by adding the appropriate switch.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl cci list --datacenter=dal05</pre></div>
<h3 id="DNS">DNS</h3>
<p>Interact with our authoritative DNS service through the <span class="geshifilter"><code class="text geshifilter-text">dns</code></span> module.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl dns
usage: sl dns [<command>] [<args>...] [options]
&nbsp;
Manage DNS
&nbsp;
The available zone commands are:
  create  Create zone
  delete  Delete zone
  list    List zones or a zone's records
  print   Print zone in BIND format
&nbsp;
The available record commands are:
  add     Add resource record
  edit    Update resource records (bulk/single)
  remove  Remove resource records</pre></div>
<p>The module contains two subsections: <span class="geshifilter"><code class="text geshifilter-text">zone</code></span> and <span class="geshifilter"><code class="text geshifilter-text">record</code></span></p>
<h4 id="Zone_Print">Zone Print</h4>
<p>The contents of a BIND zone file can be printed to the screen with the <span class="geshifilter"><code class="text geshifilter-text">print</code></span> command.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl dns print example.com
$ORIGIN example.com.
$TTL 86400
@ IN SOA ns1.softlayer.com. support.softlayer.com. (
                       2013041501        ; Serial
                       7200              ; Refresh
                       600               ; Retry
                       1728000           ; Expire
                       43200)            ; Minimum
&nbsp;
@                      86400    IN NS    ns1.softlayer.com.
@                      86400    IN NS    ns2.softlayer.com.
&nbsp;
&nbsp;
@                      86400    IN A     127.0.0.1
server01               7200     IN A     127.0.0.1</pre></div>
<h4 id="Zone_Creation">Zone Creation</h4>
<p>Create a new zone combining the <span class="geshifilter"><code class="text geshifilter-text">create</code></span> command with the path for the new zone.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl dns create phil.example.com</pre></div>
<h4 id="Record_Creation">Record Creation</h4>
<p>Zone records are created with the <span class="geshifilter"><code class="text geshifilter-text">add</code></span> command. Enter the zone along with the desired record type and corresponding record details. This example creates an A record for the IP 127.0.0.1 with a standard ttl of 86400.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl dns add phil.example.com mail A 127.0.0.1 --ttl=86400</pre></div>
<h4 id="Record_Editing">Record Editing</h4>
<p>Edit a zone record with the <span class="geshifilter"><code class="text geshifilter-text">edit</code></span> command.</p>
<div class="geshifilter">
<pre class="text geshifilter-text" style="font-family:monospace;">$ sl dns edit phil.example.com mail --data=192.168.1.1</pre></div>

