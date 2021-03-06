<a name="module_foobar-control-http"></a>

## foobar-control-http

* [foobar-control-http](#module_foobar-control-http)
    * [~Foobar](#module_foobar-control-http..Foobar)
    * [~FoobarControl](#module_foobar-control-http..FoobarControl)
        * [.getStatus()](#module_foobar-control-http..FoobarControl+getStatus) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.queueItem(itemIndex)](#module_foobar-control-http..FoobarControl+queueItem) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.dequeueItem(itemIndex)](#module_foobar-control-http..FoobarControl+dequeueItem) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.setFocus(itemIndex)](#module_foobar-control-http..FoobarControl+setFocus) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.removeItem(itemIndex)](#module_foobar-control-http..FoobarControl+removeItem) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.seek(percent)](#module_foobar-control-http..FoobarControl+seek) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.playbackOrder(playbackOrder)](#module_foobar-control-http..FoobarControl+playbackOrder) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.volume(volume)](#module_foobar-control-http..FoobarControl+volume) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.stopAfterCurrent(sac)](#module_foobar-control-http..FoobarControl+stopAfterCurrent) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.stopAfterQueue(saq)](#module_foobar-control-http..FoobarControl+stopAfterQueue) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.queueRandomItems(itemsCount)](#module_foobar-control-http..FoobarControl+queueRandomItems) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.switchPlaylist(playlistIndex)](#module_foobar-control-http..FoobarControl+switchPlaylist) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.playlistPage(playlistPage)](#module_foobar-control-http..FoobarControl+playlistPage) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.stop()](#module_foobar-control-http..FoobarControl+stop) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.playOrPause()](#module_foobar-control-http..FoobarControl+playOrPause) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.previous()](#module_foobar-control-http..FoobarControl+previous) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.next()](#module_foobar-control-http..FoobarControl+next) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.random()](#module_foobar-control-http..FoobarControl+random) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.queueAlbum()](#module_foobar-control-http..FoobarControl+queueAlbum) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.emptyPlaylist()](#module_foobar-control-http..FoobarControl+emptyPlaylist) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
        * [.start(trackIndex)](#module_foobar-control-http..FoobarControl+start) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>

<a name="module_foobar-control-http..Foobar"></a>

### foobar-control-http~Foobar
Contains types used by FoobarControl.

**Kind**: inner property of [<code>foobar-control-http</code>](#module_foobar-control-http)  
<a name="module_foobar-control-http..FoobarControl"></a>

### foobar-control-http~FoobarControl
Control an instance of foobar2000 through 'foo_httpcontrol' and 'ajquery'.

**Kind**: inner property of [<code>foobar-control-http</code>](#module_foobar-control-http)  

* [~FoobarControl](#module_foobar-control-http..FoobarControl)
    * [.getStatus()](#module_foobar-control-http..FoobarControl+getStatus) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.queueItem(itemIndex)](#module_foobar-control-http..FoobarControl+queueItem) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.dequeueItem(itemIndex)](#module_foobar-control-http..FoobarControl+dequeueItem) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.setFocus(itemIndex)](#module_foobar-control-http..FoobarControl+setFocus) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.removeItem(itemIndex)](#module_foobar-control-http..FoobarControl+removeItem) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.seek(percent)](#module_foobar-control-http..FoobarControl+seek) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.playbackOrder(playbackOrder)](#module_foobar-control-http..FoobarControl+playbackOrder) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.volume(volume)](#module_foobar-control-http..FoobarControl+volume) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.stopAfterCurrent(sac)](#module_foobar-control-http..FoobarControl+stopAfterCurrent) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.stopAfterQueue(saq)](#module_foobar-control-http..FoobarControl+stopAfterQueue) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.queueRandomItems(itemsCount)](#module_foobar-control-http..FoobarControl+queueRandomItems) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.switchPlaylist(playlistIndex)](#module_foobar-control-http..FoobarControl+switchPlaylist) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.playlistPage(playlistPage)](#module_foobar-control-http..FoobarControl+playlistPage) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.stop()](#module_foobar-control-http..FoobarControl+stop) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.playOrPause()](#module_foobar-control-http..FoobarControl+playOrPause) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.previous()](#module_foobar-control-http..FoobarControl+previous) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.next()](#module_foobar-control-http..FoobarControl+next) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.random()](#module_foobar-control-http..FoobarControl+random) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.queueAlbum()](#module_foobar-control-http..FoobarControl+queueAlbum) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.emptyPlaylist()](#module_foobar-control-http..FoobarControl+emptyPlaylist) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
    * [.start(trackIndex)](#module_foobar-control-http..FoobarControl+start) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>

<a name="module_foobar-control-http..FoobarControl+getStatus"></a>

#### foobarControl.getStatus() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Get the player's current status.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+queueItem"></a>

#### foobarControl.queueItem(itemIndex) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Add an item into the queue by its index in the current playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| itemIndex | <code>number</code> | The 0-based index in the current playlist of the item to add to the queue. |

<a name="module_foobar-control-http..FoobarControl+dequeueItem"></a>

#### foobarControl.dequeueItem(itemIndex) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Remove at item from the queue by its index in the current playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| itemIndex | <code>number</code> | The 0-based index in the current playlist of the item to remove from the queue. |

<a name="module_foobar-control-http..FoobarControl+setFocus"></a>

#### foobarControl.setFocus(itemIndex) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Set the cursor position to an item by its index in the current playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| itemIndex | <code>number</code> | The 0-based index in the current playlist of the item to set cursor position to. |

<a name="module_foobar-control-http..FoobarControl+removeItem"></a>

#### foobarControl.removeItem(itemIndex) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Remove an item from the current playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| itemIndex | <code>number</code> | The 0-based index in the current playlist of the item to remove. |

<a name="module_foobar-control-http..FoobarControl+seek"></a>

#### foobarControl.seek(percent) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Set the caret to a certain percentage through the track.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| percent | <code>number</code> | The desired progress through the track, as a fraction of 1. |

<a name="module_foobar-control-http..FoobarControl+playbackOrder"></a>

#### foobarControl.playbackOrder(playbackOrder) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Set the playback order.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| playbackOrder | <code>Foobar.PlaybackOrder</code> | The desired playback order. |

<a name="module_foobar-control-http..FoobarControl+volume"></a>

#### foobarControl.volume(volume) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Set the volume level.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| volume | <code>number</code> | The desired volume as a fraction of 1. |

<a name="module_foobar-control-http..FoobarControl+stopAfterCurrent"></a>

#### foobarControl.stopAfterCurrent(sac) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Set the status of the 'stop after current' flag.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| sac | <code>boolean</code> | The desired flag status. |

<a name="module_foobar-control-http..FoobarControl+stopAfterQueue"></a>

#### foobarControl.stopAfterQueue(saq) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Set the status of the 'stop after queue' flag.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| saq | <code>boolean</code> | The desired flag status. |

<a name="module_foobar-control-http..FoobarControl+queueRandomItems"></a>

#### foobarControl.queueRandomItems(itemsCount) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Add a certain number of random items to the queue.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| itemsCount | <code>number</code> | The number of items to add. |

<a name="module_foobar-control-http..FoobarControl+switchPlaylist"></a>

#### foobarControl.switchPlaylist(playlistIndex) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Switch playback to another playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| playlistIndex | <code>number</code> | The 0-based index of the playlist to switch to. |

<a name="module_foobar-control-http..FoobarControl+playlistPage"></a>

#### foobarControl.playlistPage(playlistPage) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Switch the view window to another page of the playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| playlistPage | <code>number</code> | The 0-based page to switch to. |

<a name="module_foobar-control-http..FoobarControl+stop"></a>

#### foobarControl.stop() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Stop playback.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+playOrPause"></a>

#### foobarControl.playOrPause() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Pause or resume playback.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+previous"></a>

#### foobarControl.previous() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Move playback to the previous track.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+next"></a>

#### foobarControl.next() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Move playback to the next track.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+random"></a>

#### foobarControl.random() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Move playback to a random track.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+queueAlbum"></a>

#### foobarControl.queueAlbum() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Add the current track's album to the queue.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+emptyPlaylist"></a>

#### foobarControl.emptyPlaylist() ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Empty the current playlist.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  
<a name="module_foobar-control-http..FoobarControl+start"></a>

#### foobarControl.start(trackIndex) ⇒ <code>Promise.&lt;Foobar.Status&gt;</code>
Start playing, optionally specifying a specific track to play.

**Kind**: instance method of [<code>FoobarControl</code>](#module_foobar-control-http..FoobarControl)  

| Param | Type | Description |
| --- | --- | --- |
| trackIndex | <code>number</code> | The 0-based index in the current playlist of the track to play. |

