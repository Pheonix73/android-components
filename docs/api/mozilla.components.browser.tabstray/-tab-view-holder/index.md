[android-components](../../index.md) / [mozilla.components.browser.tabstray](../index.md) / [TabViewHolder](./index.md)

# TabViewHolder

`class TabViewHolder : ViewHolder, `[`Observer`](../../mozilla.components.browser.session/-session/-observer/index.md) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/tabstray/src/main/java/mozilla/components/browser/tabstray/TabViewHolder.kt#L21)

A RecyclerView ViewHolder implementation for "tab" items.

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `TabViewHolder(itemView: `[`View`](https://developer.android.com/reference/android/view/View.html)`, tabsTray: `[`BrowserTabsTray`](../-browser-tabs-tray/index.md)`)`<br>A RecyclerView ViewHolder implementation for "tab" items. |

### Functions

| Name | Summary |
|---|---|
| [bind](bind.md) | `fun bind(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, isSelected: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, observable: `[`Observable`](../../mozilla.components.support.base.observer/-observable/index.md)`<`[`Observer`](../../mozilla.components.concept.tabstray/-tabs-tray/-observer/index.md)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Displays the data of the given session and notifies the given observable about events. |
| [onUrlChanged](on-url-changed.md) | `fun onUrlChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, url: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [unbind](unbind.md) | `fun unbind(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>The attached view no longer needs to display any data. |

### Inherited Functions

| Name | Summary |
|---|---|
| [onAppPermissionRequested](../../mozilla.components.browser.session/-session/-observer/on-app-permission-requested.md) | `open fun onAppPermissionRequested(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, permissionRequest: `[`PermissionRequest`](../../mozilla.components.concept.engine.permission/-permission-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onCloseWindowRequested](../../mozilla.components.browser.session/-session/-observer/on-close-window-requested.md) | `open fun onCloseWindowRequested(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, windowRequest: `[`WindowRequest`](../../mozilla.components.concept.engine.window/-window-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onContentPermissionRequested](../../mozilla.components.browser.session/-session/-observer/on-content-permission-requested.md) | `open fun onContentPermissionRequested(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, permissionRequest: `[`PermissionRequest`](../../mozilla.components.concept.engine.permission/-permission-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onCustomTabConfigChanged](../../mozilla.components.browser.session/-session/-observer/on-custom-tab-config-changed.md) | `open fun onCustomTabConfigChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, customTabConfig: `[`CustomTabConfig`](../../mozilla.components.browser.session.tab/-custom-tab-config/index.md)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDesktopModeChanged](../../mozilla.components.browser.session/-session/-observer/on-desktop-mode-changed.md) | `open fun onDesktopModeChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, enabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onDownload](../../mozilla.components.browser.session/-session/-observer/on-download.md) | `open fun onDownload(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, download: `[`Download`](../../mozilla.components.browser.session/-download/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onFindResult](../../mozilla.components.browser.session/-session/-observer/on-find-result.md) | `open fun onFindResult(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, result: `[`FindResult`](../../mozilla.components.browser.session/-session/-find-result/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onFullScreenChanged](../../mozilla.components.browser.session/-session/-observer/on-full-screen-changed.md) | `open fun onFullScreenChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, enabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onLoadingStateChanged](../../mozilla.components.browser.session/-session/-observer/on-loading-state-changed.md) | `open fun onLoadingStateChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, loading: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onLongPress](../../mozilla.components.browser.session/-session/-observer/on-long-press.md) | `open fun onLongPress(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, hitResult: `[`HitResult`](../../mozilla.components.concept.engine/-hit-result/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onNavigationStateChanged](../../mozilla.components.browser.session/-session/-observer/on-navigation-state-changed.md) | `open fun onNavigationStateChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, canGoBack: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`, canGoForward: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onOpenWindowRequested](../../mozilla.components.browser.session/-session/-observer/on-open-window-requested.md) | `open fun onOpenWindowRequested(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, windowRequest: `[`WindowRequest`](../../mozilla.components.concept.engine.window/-window-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onProgress](../../mozilla.components.browser.session/-session/-observer/on-progress.md) | `open fun onProgress(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, progress: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onPromptRequested](../../mozilla.components.browser.session/-session/-observer/on-prompt-requested.md) | `open fun onPromptRequested(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, promptRequest: `[`PromptRequest`](../../mozilla.components.concept.engine.prompt/-prompt-request/index.md)`): `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [onSearch](../../mozilla.components.browser.session/-session/-observer/on-search.md) | `open fun onSearch(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, searchTerms: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onSecurityChanged](../../mozilla.components.browser.session/-session/-observer/on-security-changed.md) | `open fun onSecurityChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, securityInfo: `[`SecurityInfo`](../../mozilla.components.browser.session/-session/-security-info/index.md)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onThumbnailChanged](../../mozilla.components.browser.session/-session/-observer/on-thumbnail-changed.md) | `open fun onThumbnailChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, bitmap: `[`Bitmap`](https://developer.android.com/reference/android/graphics/Bitmap.html)`?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onTitleChanged](../../mozilla.components.browser.session/-session/-observer/on-title-changed.md) | `open fun onTitleChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, title: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onTrackerBlocked](../../mozilla.components.browser.session/-session/-observer/on-tracker-blocked.md) | `open fun onTrackerBlocked(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, blocked: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, all: `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [onTrackerBlockingEnabledChanged](../../mozilla.components.browser.session/-session/-observer/on-tracker-blocking-enabled-changed.md) | `open fun onTrackerBlockingEnabledChanged(session: `[`Session`](../../mozilla.components.browser.session/-session/index.md)`, blockingEnabled: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |