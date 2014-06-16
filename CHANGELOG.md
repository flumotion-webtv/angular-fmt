<a name="0.1.3"></a>
### 0.1.3 (2014-06-16)


#### Bug Fixes

* **player:**
  * fix player SWF base path ((74196ec7))


#### Features

* **player:** fmt-player callback to manage it using the Video.js API [#72439970] ((e8d18e30))


#### Breaking Changes

* Now 'audio/current' won't be automatically added to the path.

To migrate, change your code to the following:

`player-swf-base-url="path-to-players-folder/"`

To:

`player-swf-base-url="path-to-players-folder/audio/current"`
 ((74196ec7))


<a name="0.1.2"></a>
### 0.1.2 (2014-06-05)


#### Bug Fixes

* **addthis:** use current url to share with AddThis as default ((c8a39e76))
* **player:** don't initialize the player if videojs is not loaded yet ((1b4c97e9))
* **playlist:**
  * fix playlist dimensions ((07e28260))
  * use current location for contents with relative URLs ((1e75f7d4))
  * skip class col-md-12 if no columns defined ((4c5f60e7))
  * append window.fmtBaseUrl in case it is defined ((244b553e))
  * ID matching the URL ignores if it is string or int ((4f6017d0))


#### Features

* **dash:**
  * Support DASH using MSE libs ((5515ad88))
  * [#70839114] Add support for MPEG-DASH ((3e5428b3))
* **layout:** new directive fmt-layout ((63ce928d))
* **playlist:**
  * include position in the new item selected dispatching event ((a5d5d5a9))
  * obtain items from paginated responses ((2ff1020c))
* **widget:**
  * new configuration attribute to setup a widget ((ec1eac5a))
  * add directive fmt-widget ((cccdeb9c))


<a name="0.1.1"></a>
### 0.1.1 (2014-05-19)


#### Bug Fixes

* **playlist:**
  * skip class col-md-12 if no columns defined ((4c5f60e7))
  * append window.fmtBaseUrl in case it is defined ((244b553e))
  * ID matching the URL ignores if it is string or int ((4f6017d0))


#### Features

* **dash:**
  * Support DASH using MSE libs ((5515ad88))
  * [#70839114] Add support for MPEG-DASH ((3e5428b3))
* **playlist:**
  * include position in the new item selected dispatching event ((a5d5d5a9))
  * obtain items from paginated responses ((2ff1020c))


<a name="0.1.0"></a>
## 0.1.0 (2014-05-14)


#### Features

_Very first, initial release_.

Version `0.1.0` was released with the following directives:

* player
* player-dash
* playlist
* addthis