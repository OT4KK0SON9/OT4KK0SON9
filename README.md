<h1>
  Halo Bang

  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="40px"/>
<h1>




class="btn">    Cancel
</button>
          <button form="code-search-feedback-form" data-action="click:qbsearch-input#submitFeedback" type="submit" data-view-component="true" class="btn-primary btn">    Submit feedback
</button>
</div>
</dialog></dialog-helper>

    <custom-scopes data-target="qbsearch-input.customScopesManager">

<dialog-helper>
  <dialog data-target="custom-scopes.customScopesModalDialog" data-action="close:qbsearch-input#handleDialogClose cancel:qbsearch-input#handleDialogClose" id="custom-scopes-dialog" aria-modal="true" aria-labelledby="custom-scopes-dialog-title" aria-describedby="custom-scopes-dialog-description" data-view-component="true" class="Overlay Overlay-whenNarrow Overlay--size-medium Overlay--motion-scaleFade">
    <div data-view-component="true" class="Overlay-header Overlay-header--divided">
  <div class="Overlay-headerContentWrap">
    <div class="Overlay-titleWrap">
      <h1 class="Overlay-title " id="custom-scopes-dialog-title">
        Saved searches
      </h1>
        <h2 id="custom-scopes-dialog-description" class="Overlay-description">Use saved searches to filter your results more quickly</h2>
    </div>
    <div class="Overlay-actionWrap">
      <button data-close-dialog-id="custom-scopes-dialog" aria-label="Close" type="button" data-view-component="true" class="close-button Overlay-closeButton"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>
</svg></button>
    </div>
  </div>
</div>
      <scrollable-region data-labelled-by="custom-scopes-dialog-title">
        <div data-view-component="true" class="Overlay-body">        <div data-target="custom-scopes.customScopesModalDialogFlash"></div>

        <div hidden class="create-custom-scope-form" data-target="custom-scopes.createCustomScopeForm">
        <!-- '"` --><!-- </textarea></xmp> --></option></form><form id="custom-scopes-dialog-form" data-turbo="false" action="/search/custom_scopes" accept-charset="UTF-8" method="post"><input type="hidden" data-csrf="true" name="authenticity_token" value="X3uGDPepdU5nR16/KfGWy5mIuB8OM+rwxXy4+LO/Ji+NQxWdUticNXYuJWf/iVgHeqQGKyPm6anSXGy1Tqv43Q==" />
          <div data-target="custom-scopes.customScopesModalDialogFlash"></div>

          <input type="hidden" id="custom_scope_id" name="custom_scope_id" data-target="custom-scopes.customScopesIdField">

          <div class="form-group">
            <label for="custom_scope_name">Name</label>
            <auto-check src="/search/custom_scopes/check_name" required>
              <input
                type="text"
                name="custom_scope_name"
                id="custom_scope_name"
                data-target="custom-scopes.customScopesNameField"
                class="form-control"
                autocomplete="off"
                placeholder="github-ruby"
                required
                maxlength="50">
              <input type="hidden" data-csrf="true" value="HIv/4sbJ0OyQPrwcGdesyu5+ix/VYukcpeM+8L9JcAX0i4MF5IIIwi6M9333wrUeGZkKQTB1UjynjCCw3XmVLA==" />
            </auto-check>
          </div>

          <div class="form-group">
            <label for="custom_scope_query">Query</label>
            <input
              type="text"
              name="custom_scope_query"
              id="custom_scope_query"
              data-target="custom-scopes.customScopesQueryField"
              class="form-control"
              autocomplete="off"
              placeholder="(repo:mona/a OR repo:mona/b) AND lang:python"
              required
              maxlength="500">
          </div>

          <p class="text-small color-fg-muted">
            To see all available qualifiers, see our <a class="Link--inTextBlock" href="https://docs.github.com/search-github/github-code-search/understanding-github-code-search-syntax">documentation</a>.
          </p>
</form>        </div>

        <div data-target="custom-scopes.manageCustomScopesForm">
          <div data-target="custom-scopes.list"></div>                         </div>

</div>
      </scrollable-region>
      <div data-view-component="true" class="Overlay-footer Overlay-footer--alignEnd Overlay-footer--divided">          <button data-action="click:custom-scopes#customScopesCancel" type="button" data-view-component="true" class="btn">    Cancel
</button>
          <button form="custom-scopes-dialog-form" data-action="click:custom-scopes#customScopesSubmit" data-target="custom-scopes.customScopesSubmitButton" type="submit" data-view-component="true" class="btn-primary btn">    Create saved search                                       </button>
</div>                                                                 </dialog></dialog-helper>
    </custom-scopes>                                                     </div>
</qbsearch-input><input type="hidden" data-csrf="true" class="js-data-jump-to-suggestions-path-csrf" value="Sh/iwe1i4P9ID6/mKH8FXJ3XBmvry13av7zcayODvlU/Wcvmo3uwjPlpplyCX16UEnlkYTMqp6wrp59j86s1uQ==" />

                                                                                 <div class="position-relative mr-lg-3 d-lg-inline-block">                <a href="/login?return_to=https%3A%2F%2Fgithub.com%2FOT4KK0SON9"                                                                                class="HeaderMenu-link HeaderMenu-link--sign-in flex-shrink-0 no-underline d-block d-lg-inline-block border border-lg-0 rounded rounded-lg-0 p-2 p-lg-0"                                                             data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;originating_url&quot;:&quot;https://github.com/OT4KK0SON9&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="4c649a53c5395e4790f829613e614f4c7e199d93854cad4ea25e9bad92ec3448"                                                                                    data-ga-click="(Logged out) Header, clicked Sign in, text:sign-in">                                                                           Sign in                                                              </a>                                                                 </div>                                                                                                                                          <a href="/signup?ref_cta=Sign+up&amp;ref_loc=header+logged+out&amp;ref_page=%2F%3Cuser-name%3E&amp;source=header"
              class="HeaderMenu-link HeaderMenu-link--sign-up flex-shrink-0 d-none d-lg-inline-block no-underline border color-border-default rounded px-2 py-1"
              data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;site header menu&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;SIGN_UP&quot;,&quot;originating_url&quot;:&quot;https://github.com/OT4KK0SON9&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="4c649a53c5395e4790f829613e614f4c7e199d93854cad4ea25e9bad92ec3448"                                                                                    data-analytics-event="{&quot;category&quot;:&quot;Sign up&quot;,&quot;action&quot;:&quot;click to sign up for account&quot;,&quot;label&quot;:&quot;ref_page:/&lt;user-name&gt;;ref_cta:Sign up;ref_loc:header logged out&quot;}"
            >
              Sign up
            </a>
        </div>                                                               </div>                                                               </div>                                                               </div>                                                               </header>                                                                                                                                           <div hidden="hidden" data-view-component="true" class="js-stale-session-flash stale-session-flash flash flash-warn flash-full mb-3">
                                                                               <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">                                                                       <path d="M6.457 1.047c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0 1 14.082 15H1.918a1.75 1.75 0 0 1-1.543-2.575Zm1.763.707a.25.25 0 0 0-.44 0L1.698 13.132a.25.25 0 0 0 .22.368h12.164a.25.25 0 0 0 .22-.368Zm.53 3.996v2.5a.75.75 0 0 1-1.5 0v-2.5a.75.75 0 0 1 1.5 0ZM9 11a1 1 0 1 1-2 0 1 1 0 0 1 2 0Z"></path>
</svg>                                                                         <span class="js-stale-session-flash-signed-in" hidden>You signed in with another tab or window. <a class="Link--inTextBlock" href="">Reload</a> to refresh your session.</span>
        <span class="js-stale-session-flash-signed-out" hidden>You signed out in another tab or window. <a class="Link--inTextBlock" href="">Reload</a> to refresh your session.</span>
        <span class="js-stale-session-flash-switched" hidden>You switched accounts on another tab or window. <a class="Link--inTextBlock" href="">Reload</a> to refresh your session.</span>
                                                                           <button id="icon-button-cab8bb8e-8d0a-489f-b705-24d22faec6e1" aria-labelledby="tooltip-834e198c-4acf-4dbf-b7a7-b375a0da0d62" type="button" data-view-component="true" class="Button Button--iconOnly Button--invisible Button--medium flash-close js-flash-close">  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x Button-visual">                  <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>                                                                </svg>
</button><tool-tip id="tooltip-834e198c-4acf-4dbf-b7a7-b375a0da0d62" for="icon-button-cab8bb8e-8d0a-489f-b705-24d22faec6e1" popover="manual" data-direction="s" data-type="label" data-view-component="true" class="sr-only position-absolute">Dismiss alert</tool-tip>                                                                                                                                                                   
</div>                                                                     </div>                                                                                                                                      <div id="start-of-content" class="show-on-focus"></div>
                                                                                                                                                                                                                     
                                                                                                                                                                                                                     
    <div id="js-flash-container" class="flash-container" data-turbo-replace>                                                                  
                                                                                                                                              
                                                                         <template class="js-flash-template">                                                                                                        <div class="flash flash-full   {{ className }}">
  <div >                                                                   <button autofocus class="flash-close js-flash-close" type="button" aria-label="Dismiss this message">                                           <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">      <path d="M3.72 3.72a.75.75 0 0 1 1.06 0L8 6.94l3.22-3.22a.749.749 0 0 1 1.275.326.749.749 0 0 1-.215.734L9.06 8l3.22 3.22a.749.749 0 0 1-.326 1.275.749.749 0 0 1-.734-.215L8 9.06l-3.22 3.22a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042L6.94 8 3.72 4.78a.75.75 0 0 1 0-1.06Z"></path>                                                                </svg>
    </button>                                                              <div aria-atomic="true" role="alert" class="js-flash-alert">       
      <div>{{ message }}</div>                                                                                                                    </div>                                                               </div>
</div>                                                                   </template>                                                          </div>                                                                 
                                                                                                                                                  <include-fragment class="js-notification-shelf-include-fragment" data-base-src="https://github.com/notifications/beta/shelf"></include-fragment>                                                                                                                                        
                                                                                                                                                                                                                       <div
    class="application-main "                                              data-commit-hovercards-enabled                                         data-discussion-hovercards-enabled
    data-issue-and-pr-hovercards-enabled                                 >                                                                          <main>                                                           
<x-banner data-dismiss-scheme="none" data-view-component="true">         <div hidden="hidden" data-view-component="true" class="js-user-status-banner Banner flash Banner--full flash-full">                               <div class="Banner-visual">
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-info">
    <path d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8Zm8-6.5a6.5 6.5 0 1 0 0 13 6.5 6.5 0 0 0 0-13ZM6.5 7.75A.75.75 0 0 1 7.25 7h1a.75.75 0 0 1 .75.75v2.75h.25a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1 0-1.5h.25v-2h-.25a.75.75 0 0 1-.75-.75ZM8 6a1 1 0 1 1 0-2 1 1 0 0 1 0 2Z"></path>
</svg>                                                                       </div>                                                               <div data-view-component="true" class="Banner-message">                  <p class="Banner-title" data-target="x-banner.titleText">
  <span class="js-user-status-banner-message" aria-live="polite"></span>                                                                      </p>
</div></div></x-banner>                                                  <div                                                                     class="mt-4 position-sticky top-0 d-none d-md-block color-bg-default width-full border-bottom
      color-border-muted"                                                  style="z-index:3;"                                                     data-turbo-frame="user-profile-frame"
  >                                                                        <div class="container-xl px-3 px-md-4 px-lg-5">                            <div data-view-component="true" class="Layout Layout--flowRow-until-md Layout--sidebarPosition-start Layout--sidebarPosition-flowRow-start">                                                                                                                                          <div data-view-component="true" class="Layout-sidebar">            <div class="user-profile-sticky-bar">
              <div class="user-profile-mini-vcard d-table">
                <span class="user-profile-mini-avatar d-table-cell v-align-middle lh-condensed-ultra pr-2">
                  <img class="rounded-2 avatar-user" src="https://avatars.githubusercontent.com/u/160365589?s=64&amp;v=4" width="32" height="32" alt="@OT4KK0SON9" />                                                                </span>
                <span class="d-table-cell v-align-middle lh-condensed">                  <strong>OT4KK0SON9</strong>

  <span class="user-following-container">
    <span class="follow d-block">
      <a class="btn btn-sm mini-follow-button" data-hydro-click="{&quot;event_type&quot;:&quot;authentication.click&quot;,&quot;payload&quot;:{&quot;location_in_page&quot;:&quot;follow button&quot;,&quot;repository_id&quot;:null,&quot;auth_type&quot;:&quot;LOG_IN&quot;,&quot;originating_url&quot;:&quot;https://github.com/OT4KK0SON9&quot;,&quot;user_id&quot;:null}}" data-hydro-click-hmac="01ef8dbe8d0952f2a2ccfa4a2738ba78d80a8585713dd9e03b75f0970f1a39b2" href="/login?return_to=https%3A%2F%2Fgithub.com%2FOT4KK0SON9">Follow</a>                                           </span>                                                              </span>                                                                                                                                                     </span>                                                              </div>                                                               </div>
</div>
  <div data-view-component="true" class="Layout-main">            <div class="UnderlineNav width-full box-shadow-none js-responsive-underlinenav overflow-md-x-hidden">
              <nav class="UnderlineNav-body width-full p-responsive js-sidenav-container-pjax" aria-label="User profile">
  <a aria-current="page" class="UnderlineNav-item js-responsive-underlinenav-item js-selected-navigation-item selected" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:160365589,&quot;target&quot;:&quot;TAB_OVERVIEW&quot;,&quot;user_id&quot;:null,&quot;originating_url&quot;:&quot;https://github.com/OT4KK0SON9&quot;}}" data-hydro-click-hmac="34326d0ed0c9521bd1f7353a2c220be098be7ccb3775d04823cd05ec3f12575b" data-tab-item="overview" data-selected-links="overview /OT4KK0SON9" href="/OT4KK0SON9">                                                                         <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-book UnderlineNav-octicon hide-sm">                                               <path d="M0 1.75A.75.75 0 0 1 .75 1h4.253c1.227 0 2.317.59 3 1.501A3.743 3.743 0 0 1 11.006 1h4.245a.75.75 0 0 1 .75.75v10.5a.75.75 0 0 1-.75.75h-4.507a2.25 2.25 0 0 0-1.591.659l-.622.621a.75.75 0 0 1-1.06 0l-.622-.621A2.25 2.25 0 0 0 5.258 13H.75a.75.75 0 0 1-.75-.75Zm7.251 10.324.004-5.073-.002-2.253A2.25 2.25 0 0 0 5.003 2.5H1.5v9h3.757a3.75 3.75 0 0 1 1.994.574ZM8.755 4.75l-.004 7.322a3.752 3.752 0 0 1 1.992-.572H14.5v-9h-3.495a2.25 2.25 0 0 0-2.25 2.25Z"></path>
</svg>
    Overview
</a>
  <a class="UnderlineNav-item js-responsive-underlinenav-item js-selected-navigation-item" data-hydro-click="{&quot;event_type&quot;:&quot;user_profile.click&quot;,&quot;payload&quot;:{&quot;profile_user_id&quot;:160365589,&quot;target&quot;:&quot;TAB_REPOSITORIES&qu
