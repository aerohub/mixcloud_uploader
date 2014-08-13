Mixcloud CLI Uploader
====================================

Overview
--------

A go CLI application that uploads MP3's (cloudcasts)

It can:
 * Add descriptions
 * Add tags
 * Add cover art
 * Parse Virtual DJ 7 Tracklist.txt sections to approximate track changes

Source Requirements
------------

* GoLang > 1.2.1
* The Internet

Using Mixcloud CLI Uploader From Source
--------------------------------

  1. Goto http://www.mixcloud.com/developers/ and create a new application
  1. cp build/oauth_client.env.sample build/oauth_client.env
  1. Fill out build/oauth_client.env with your Oauth Application details from step 1
  1. Run bin/build
  1. Run the built packages as below from pkg/

Using Pre-compiled Packages
---------------------------

Using compiled packages:

  `mixcloud --file <path_to_filename> --cover <path_to_cover> --tracklist <path_to_tracklist>`

Meta
----

* Code: `git clone git://github.com/ruxton/mixcloud_uploader.git`
