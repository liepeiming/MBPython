# window (object)

Table of contents:
* [Methods](#methods)
  * [wkeCreateWebWindow](#wkeCreateWebWindow)
  * [wkeShowWindow](#wkeShowWindow)
  * [wkeCreateWebView](#wkeCreateWebView)
  * [wkeDestroyWebView](#wkeDestroyWebView)
  * [wkeMoveToCenter](#wkeMoveToCenter)
  * [wkeRunMessageLoop](#wkeRunMessageLoop)
  * [wkeSetUserAgentW](#wkeSetUserAgentW)
  * [wkeSetDragEnable](#wkeSetDragEnable)
  * [wkeAddPluginDirectory](#wkeAddPluginDirectory)
  * [wkeSetNpapiPluginsEnabled](#wkeSetNpapiPluginsEnabled)
  * [wkeSetCspCheckEnable](#wkeSetCspCheckEnable)
  * [wkeSetDebugConfig](#wkeSetDebugConfig)
  * [wkeSetNavigationToNewWindowEnable](#wkeSetNavigationToNewWindowEnable)
  * [wkeSetWebViewName](#wkeSetWebViewName)
  * [wkeSetZoomFactor](#wkeSetZoomFactor)
  * [wkeSetContextMenuEnabled](#wkeSetContextMenuEnabled)
  * [wkeSetWindowTitleW](#wkeSetWindowTitleW)
  * [wkeSetTransparent](#wkeSetTransparent)
  * [wkeSetHandle](#wkeSetHandle)
  * [wkeResize](#wkeResize)
  * [wkeWidth](#wkeWidth)
  * [wkeHeight](#wkeHeight)
  * [wkeContentsWidth](#wkeContentsWidth)
  * [wkeContentsHeight](#wkeContentsHeight)
  * [wkeGoForward](#wkeGoForward)
  * [wkeGoBack](#wkeGoBack)
  * [wkeGetWindowHandle](#wkeGetWindowHandle)
  * [wkeGetViewDC](#wkeGetViewDC)
  * [wkeSetTouchEnabled](#wkeSetTouchEnabled)
  * [simulate_device](#simulate_device)
  * [bind_window](#bind_window)
## Methods
### wkeCreateWebWindow

| Parameter | Type | description
| --- | --- | --- |
| _type | int |0:normal window,1:transparent window,3:embedded window |
| x | int | x axis |
| y | int | y axis |
| width | int | window's width |
| height | int | window's height |
| hwnd | int |embedded other window's handle |
| __Return__ | int | webview |

### wkeShowWindow

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeCreateWebView

| Parameter | Type | description
| --- | --- | --- |
| __Return__ | int | webview |

### wkeDestroyWebView

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | None | -- |

### wkeMoveToCenter

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | None | -- |

### wkeRunMessageLoop

| Parameter | Type | description
| --- | --- | --- |
| __Return__ | None | -- |

### wkeSetUserAgentW

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| ua | string | -- |
| __Return__ | None | -- |

### wkeGetUserAgent

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | None | -- |

### wkeSetDragEnable

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeAddPluginDirectory

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _path | string | -- |
| __Return__ | None | -- |

### wkeSetNpapiPluginsEnabled

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| _path | string | -- |
| __Return__ | None | -- |

If you want to use flash must ues this method 

### wkeSetCspCheckEnable

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeSetDebugConfig

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| debug | string | -- |
| param | string | -- |
| __Return__ | None | -- |

### wkeSetCspCheckEnable

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeSetHeadlessEnabled

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeSetNavigationToNewWindowEnable

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeSetWebViewName

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| name | string | -- |
| __Return__ | None | -- |

### wkeSetZoomFactor

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| factor | int | -- |
| __Return__ | None | -- |

### wkeSetContextMenuEnabled

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### wkeSetWindowTitleW

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| title | string | -- |
| __Return__ | None | -- |

### wkeSetHandleOffset

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| x | int | -- |
| y | int | -- |
| __Return__ | None | -- |

### wkeSetHandle

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| hwnd | int | -- |
| __Return__ | None | -- |

### wkeResize

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| width | int | -- |
| height | int | -- |
| __Return__ | None | -- |

### wkeWidth

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | int | width |

### wkeHeight

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | int | height |

### wkeContentsWidth

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | int | contentswidth |

### wkeContentsHeight

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | int | contentsheight |

### wkeGoForward

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | None | -- |

### wkeGoForward

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | None | -- |

### wkeGetWindowHandle

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | int |hwnd |

### wkeGetViewDC

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| __Return__ | int | DC |

### wkeSetTouchEnabled

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| _bool | bool | -- |
| __Return__ | None | -- |

### simulate_device

| Parameter | Type | description
| --- | --- | --- |
| webview | int | -- |
| key | string | -- |
| value | string | -- |
| _int | int | -- |
| _float | float | -- |
| __Return__ | None | -- |

### bind_window

| Parameter | Type | description
| --- | --- | --- |
| hwnd | int | -- |
| _bool | bool | -- |
| __Return__ | int | webview |