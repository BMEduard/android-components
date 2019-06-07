[android-components](../../index.md) / [mozilla.components.browser.state.action](../index.md) / [TabListAction](./index.md)

# TabListAction

`sealed class TabListAction : `[`BrowserAction`](../-browser-action.md) [(source)](https://github.com/mozilla-mobile/android-components/blob/master/components/browser/state/src/main/java/mozilla/components/browser/state/action/BrowserAction.kt#L23)

[BrowserAction](../-browser-action.md) implementations related to updating the list of [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) inside [BrowserState](../../mozilla.components.browser.state.state/-browser-state/index.md).

### Types

| Name | Summary |
|---|---|
| [AddTabAction](-add-tab-action/index.md) | `data class AddTabAction : `[`TabListAction`](./index.md)<br>Adds a new [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) to the list. |
| [RemoveAllNormalTabsAction](-remove-all-normal-tabs-action.md) | `object RemoveAllNormalTabsAction : `[`TabListAction`](./index.md)<br>Removes all non-private [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md)s. |
| [RemoveAllPrivateTabsAction](-remove-all-private-tabs-action.md) | `object RemoveAllPrivateTabsAction : `[`TabListAction`](./index.md)<br>Removes all private [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md)s. |
| [RemoveAllTabsAction](-remove-all-tabs-action.md) | `object RemoveAllTabsAction : `[`TabListAction`](./index.md)<br>Removes both private and normal [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md)s. |
| [RemoveTabAction](-remove-tab-action/index.md) | `data class RemoveTabAction : `[`TabListAction`](./index.md)<br>Removes the [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) with the given [tabId](-remove-tab-action/tab-id.md) from the list of sessions. |
| [RestoreAction](-restore-action/index.md) | `data class RestoreAction : `[`TabListAction`](./index.md)<br>Restores state from a (partial) previous state. |
| [SelectTabAction](-select-tab-action/index.md) | `data class SelectTabAction : `[`TabListAction`](./index.md)<br>Marks the [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) with the given [tabId](-select-tab-action/tab-id.md) as selected tab. |

### Inheritors

| Name | Summary |
|---|---|
| [AddTabAction](-add-tab-action/index.md) | `data class AddTabAction : `[`TabListAction`](./index.md)<br>Adds a new [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) to the list. |
| [RemoveAllNormalTabsAction](-remove-all-normal-tabs-action.md) | `object RemoveAllNormalTabsAction : `[`TabListAction`](./index.md)<br>Removes all non-private [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md)s. |
| [RemoveAllPrivateTabsAction](-remove-all-private-tabs-action.md) | `object RemoveAllPrivateTabsAction : `[`TabListAction`](./index.md)<br>Removes all private [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md)s. |
| [RemoveAllTabsAction](-remove-all-tabs-action.md) | `object RemoveAllTabsAction : `[`TabListAction`](./index.md)<br>Removes both private and normal [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md)s. |
| [RemoveTabAction](-remove-tab-action/index.md) | `data class RemoveTabAction : `[`TabListAction`](./index.md)<br>Removes the [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) with the given [tabId](-remove-tab-action/tab-id.md) from the list of sessions. |
| [RestoreAction](-restore-action/index.md) | `data class RestoreAction : `[`TabListAction`](./index.md)<br>Restores state from a (partial) previous state. |
| [SelectTabAction](-select-tab-action/index.md) | `data class SelectTabAction : `[`TabListAction`](./index.md)<br>Marks the [TabSessionState](../../mozilla.components.browser.state.state/-tab-session-state/index.md) with the given [tabId](-select-tab-action/tab-id.md) as selected tab. |