<h2>Overview</h2>
RocketTop is a real-time statistics viewer for ObjectRocket, built to look
similar to the popular Unix "top" utility.
<br><br>

Requires: <a href=http://www.python.org/>python</a><br>
          curses support (installed by default in Linux/Unix/Mac OSX)

<h2>Usage</h2>
<p>
	In order to use rockettop you will need an ObjectRocket API Key.  You will need to signup for a <a href=http://www.objectrocket.com>Objectrocket account</a>, create an instance, then select the API tab under your instance.  Copy/Paste the API key to the command line below, or put it in the configuration file.
<p>
	Rockettop reports aggregate stats across your entire instance.  That means that your data is summated across all the shards.  You are seeing total overall statistics about your MongoDB instance on ObjectRocket.

<pre>
Usage: rockettop [options]

Options:
  -h, --help           show this help message and exit
  --api_key=API_KEY    ObjectRocket API key.  See www.objectrocket.com for an account
  --refresh            Refresh every n seconds

$>python rockettop --api_key=your_api_key
</pre>

<h2>License</h2>
Copyright 2012 ObjectRocket Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

<a href=http://www.apache.org/licenses/LICENSE-2.0>http://www.apache.org/licenses/LICENSE-2.0</a>

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


