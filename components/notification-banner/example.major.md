---
layout: example
parent: component.notification-banner
type: example
index: 0
style: '.example-frame__content {padding-left: 0; padding-right: 0;}'
---

<div class="ds_notification  ds_notification--major" data-module="ds-notification">
    <div class="ds_wrapper">
        <div class="ds_notification__content  ds_notification__content--has-close">
            <div role="heading" class="visually-hidden">Important</div>

            <div class="ds_notification__text">
                <p>You've been redirected from a site that no longer exists. Find what you're looking for on <a data-banner="banner-bannername-link" href="#">something</a>.</p>
            </div>

            <button data-banner="banner-bannername-close" class="ds_notification__close  js-close-notification" type="button">
                <span class="visually-hidden">Close this notification</span>
                <svg data-banner="banner-close" class="ds_icon" aria-hidden="true" role="img"><use xlink:href="/assets/images/icons/icons.stack.svg#close-21"></use></svg>
            </button>
        </div>
    </div>
</div>
