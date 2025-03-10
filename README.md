DOCTYPE html>
<html lang="en">
    <head>
        <meta charset='utf-8'>
        <meta name="viewport" content="width=device-width, initial-scale=1" id="wixDesktopViewport"/>
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="generator" content="Wix.com Website Builder"/>
        <link rel="icon" sizes="192x192" href="https://www.wix.com/favicon.ico" type="image/x-icon"/>
        <link rel="shortcut icon" href="https://www.wix.com/favicon.ico" type="image/x-icon"/>
        <link rel="apple-touch-icon" href="https://www.wix.com/favicon.ico" type="image/x-icon"/>
        <!-- Safari Pinned Tab Icon -->
        <!-- <link rel="mask-icon" href="https://www.wix.com/favicon.ico"> -->
        <!-- Original trials -->
        <!-- Legacy Polyfills -->
        <script nomodule="" src="https://static.parastorage.com/unpkg/core-js-bundle@3.2.1/minified.js"></script>
        <script nomodule="" src="https://static.parastorage.com/unpkg/focus-within-polyfill@5.0.9/dist/focus-within-polyfill.js"></script>
        <!-- Performance API Polyfills -->
        <script>
            (function() {
                var noop = function noop() {};
                if ("performance"in window === false) {
                    window.performance = {};
                }
                window.performance.mark = performance.mark || noop;
                window.performance.measure = performance.measure || noop;
                if ("now"in window.performance === false) {
                    var nowOffset = Date.now();
                    if (performance.timing && performance.timing.navigationStart) {
                        nowOffset = performance.timing.navigationStart;
                    }
                    window.performance.now = function now() {
                        return Date.now() - nowOffset;
                    }
                    ;
                }
            }
            )();
        </script>
        <!-- Globals Definitions -->
        <script>
            (function() {
                var now = Date.now()
                window.initialTimestamps = {
                    initialTimestamp: now,
                    initialRequestTimestamp: Math.round(performance.timeOrigin ? performance.timeOrigin : now - performance.now())
                }

                window.thunderboltTag = "libs-releases-GA-local"
                window.thunderboltVersion = "1.15346.0"
            }
            )();
        </script>
        <!-- Sentry needs to load before security -->
        <!-- Essential Viewer Model -->
        <script type="application/json" id="wix-essential-viewer-model">
            {
                "fleetConfig": {
                    "fleetName": "wix-thunderbolt",
                    "type": "GA",
                    "code": 0
                },
                "mode": {
                    "qa": false,
                    "enableTestApi": false,
                    "debug": false,
                    "ssrIndicator": false,
                    "ssrOnly": false,
                    "siteAssetsFallback": "enable",
                    "versionIndicator": false
                },
                "componentsLibrariesTopology": [
                    {
                        "artifactId": "editor-elements",
                        "namespace": "wixui",
                        "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                    },
                    {
                        "artifactId": "editor-elements",
                        "namespace": "dsgnsys",
                        "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                    }
                ],
                "siteFeaturesConfigs": {
                    "sessionManager": {
                        "isRunningInDifferentSiteContext": false
                    }
                },
                "language": {
                    "userLanguage": "en"
                },
                "siteAssets": {
                    "clientTopology": {
                        "mediaRootUrl": "https:\/\/static.wixstatic.com",
                        "staticMediaUrl": "https:\/\/static.wixstatic.com\/media",
                        "moduleRepoUrl": "https:\/\/static.parastorage.com\/unpkg",
                        "fileRepoUrl": "https:\/\/static.parastorage.com\/services",
                        "siteAssetsUrl": "https:\/\/siteassets.parastorage.com",
                        "pageJsonServerUrls": [
                            "https:\/\/pages.parastorage.com",
                            "https:\/\/staticorigin.wixstatic.com",
                            "https:\/\/fallback.wix.com\/wix-html-editor-pages-webapp\/page"
                        ],
                        "pathOfTBModulesInFileRepoForFallback": "wix-thunderbolt\/dist\/"
                    }
                },
                "siteFeatures": [
                    "appMonitoring",
                    "assetsLoader",
                    "businessLogger",
                    "captcha",
                    "clickHandlerRegistrar",
                    "commonConfig",
                    "componentsLoader",
                    "componentsRegistry",
                    "consentPolicy",
                    "cyclicTabbing",
                    "environmentWixCodeSdk",
                    "environment",
                    "locationWixCodeSdk",
                    "mpaNavigation",
                    "navigationManager",
                    "navigationPhases",
                    "ooi",
                    "pages",
                    "panorama",
                    "renderer",
                    "reporter",
                    "router",
                    "scrollRestoration",
                    "seoWixCodeSdk",
                    "seo",
                    "sessionManager",
                    "siteMembersWixCodeSdk",
                    "siteMembers",
                    "siteScrollBlocker",
                    "siteWixCodeSdk",
                    "stores",
                    "structureApi",
                    "thunderboltInitializer",
                    "tpaCommons",
                    "translations",
                    "usedPlatformApis",
                    "warmupData",
                    "windowMessageRegistrar",
                    "windowWixCodeSdk",
                    "wixEmbedsApi",
                    "componentsReact",
                    "platform"
                ],
                "site": {
                    "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                    "isSEO": false
                },
                "media": {
                    "staticMediaUrl": "https:\/\/static.wixstatic.com\/media",
                    "mediaRootUrl": "https:\/\/static.wixstatic.com\/",
                    "staticVideoUrl": "https:\/\/video.wixstatic.com\/"
                },
                "requestUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                "rollout": {
                    "siteAssetsVersionsRollout": false,
                    "isDACRollout": 0,
                    "isTBRollout": false},
                    "commonConfig": {
                        "brand": "wix",
                        "host": "VIEWER",
                        "bsi": "",
                        "consentPolicy": {
                        },
                        "consentPolicyHeader": {
                        },
                        "siteRevision": "28",
                        "renderingFlow": "NONE",
                        "language": "en",
                        "locale": "es-es"
                    },
                    "interactionSampleRatio": 0.01,
                    "dynamicModelUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/v2\/dynamicmodel",
                    "accessTokensUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/v1\/access-tokens",
                    "isExcludedFromSecurityExperiments": false,
                    "experiments": {
                        "specs.thunderbolt.hardenClientGlobals_EventTarget": true,
                        "specs.thunderbolt.hardenEncodingDecoding": true,
                        "specs.thunderbolt.hardenFetchAndXHR": true,
                        "specs.thunderbolt.hardenIFrames": true,
                        "specs.thunderbolt.hardenObject": true,
                        "specs.thunderbolt.hardenTimeout": true,
                        "specs.thunderbolt.removeServiceWorker": true,
                        "specs.thunderbolt.softFreeze_TextDecoder_TextEncoder": true,
                        "specs.thunderbolt.videoLazyLoading": true,
                        "specs.thunderbolt.harden_URL_JSON": true,
                        "specs.thunderbolt.hardenCookieStoreAccess": true,
                        "specs.thunderbolt.hardenReflect": true
                    }
                }</script>
            <script>
                window.viewerModel = JSON.parse(document.getElementById('wix-essential-viewer-model').textContent)
            </script>
            <script>
                window.commonConfig = viewerModel.commonConfig
            </script>
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/handleAccessTokens.inline.4300406d.bundle.min.js">
                ( () => {
                    "use strict";
                    const e = e => "string" == typeof e ? decodeURIComponent(e).toLowerCase().trimStart() : e
                      , t = "client-session-bind"
                      , o = new Set([t, "client-binding", "svSession", "smSession", "server-session-bind", "wixSession2"].map((e => e.toLowerCase())))
                      , r = Object.getOwnPropertyDescriptor(Document.prototype, "cookie")
                      , i = (e="") => `${t}=; ${e} max-age=0; path=/; expires=Thu, 01 Jan 1970 00:00:01 GMT`
                      , n = t => {
                        const r = "string" == typeof t ? t.split("=")[0].trim() : t.name
                          , i = e(r).toLowerCase();
                        return o.has(i)
                    }
                      , s = e => {
                        let t;
                        return t = "string" == typeof e ? e.split(";").map((e => e.trim())) : e,
                        t.filter((e => !n(e)))
                    }
                      , l = "tbReady"
                      , a = "security_overrideGlobals"
                      , {isExcludedFromSecurityExperiments: c, experiments: d, siteFeaturesConfigs: u, accessTokensUrl: b} = window.viewerModel
                      , g = b
                      , m = {}
                      , h = ( () => {
                        const e = document.cookie.split(";").map((e => e.trim())).filter((e => e?.startsWith(t)))[0]?.split("=")[1];
                        return ( () => {
                            const e = `domain=${location.hostname};`
                              , t = i()
                              , o = i(e);
                            r.set.call(document, t),
                            r.set.call(document, o)
                        }
                        )(),
                        e
                    }
                    )();
                    if (h && (m["client-binding"] = h),
                    d["specs.thunderbolt.hardenFetchAndXHR"] && !c) {
                        let p = fetch;
                        function f(e) {
                            const {logger: t} = e.detail;
                            try {
                                window.tb.init({
                                    fetch: p,
                                    fetchHeaders: m
                                })
                            } catch (e) {
                                const o = new Error("TB003");
                                t.captureError(o, {
                                    tags: {
                                        feature: "thunderbolt-security"
                                    }
                                }),
                                t.meter(`${a}_${o.message}`, {
                                    paramsOverrides: {
                                        evid: "26",
                                        errorType: a,
                                        eventString: o.message
                                    }
                                }),
                                window?.viewerModel?.mode.debug && console.error(e)
                            } finally {
                                removeEventListener(l, f),
                                p = fetch
                            }
                        }
                        addEventListener(l, f)
                    } else
                        window.fetchDynamicModel = () => u.sessionManager.isRunningInDifferentSiteContext ? Promise.resolve({}) : fetch(g, {
                            credentials: "same-origin",
                            headers: m
                        }).then((function(e) {
                            if (!e.ok)
                                throw new Error(`[${e.status}]${e.statusText}`);
                            return e.json()
                        }
                        )),
                        window.dynamicModelPromise = window.fetchDynamicModel();
                    Object.defineProperty(document, "cookie", {
                        get() {
                            const e = r.get.call(document);
                            return s(e).join("; ")
                        },
                        set(t) {
                            const i = e(t.split(";")[0]);
                            [...o].every((e => !i?.startsWith(e.toLowerCase()))) && r.set.call(document, t)
                        },
                        enumerable: !0,
                        configurable: !1
                    }),
                    d["specs.thunderbolt.hardenCookieStoreAccess"] && ( () => {
                        if (!globalThis.cookieStore)
                            return;
                        const e = globalThis.cookieStore.get.bind(globalThis.cookieStore)
                          , t = globalThis.cookieStore.getAll.bind(globalThis.cookieStore)
                          , r = globalThis.cookieStore.set.bind(globalThis.cookieStore)
                          , i = globalThis.cookieStore.delete.bind(globalThis.cookieStore);
                        Object.defineProperty(globalThis.CookieStore.prototype, "get", {
                            value: async t => o.has(t.toLowerCase()) ? null : e.call(void 0, t),
                            enumerable: !0,
                            configurable: !1
                        }),
                        Object.defineProperty(globalThis.CookieStore.prototype, "getAll", {
                            value: async () => {
                                const e = await t.call(void 0);
                                return s(e)
                            }
                            ,
                            enumerable: !0,
                            configurable: !1
                        }),
                        Object.defineProperty(globalThis.CookieStore.prototype, "set", {
                            value: async (...e) => {
                                const t = 1 === e.length ? e[0].name : e[0];
                                if (!n(t))
                                    return r.call(void 0, ...e)
                            }
                            ,
                            enumerable: !0,
                            configurable: !1
                        }),
                        Object.defineProperty(globalThis.CookieStore.prototype, "delete", {
                            value: async (...e) => {
                                const t = 1 === e.length ? e[0].name : e[0];
                                if (!n(t))
                                    return i.call(void 0, ...e)
                            }
                            ,
                            enumerable: !0,
                            configurable: !1
                        })
                    }
                    )()
                }
                )();
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/handleAccessTokens.inline.4300406d.bundle.min.js.map
            </script>
            <!-- Overriding Globals JS  -->
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/overrideGlobals.inline.45eeaad6.bundle.min.js">
                ( () => {
                    "use strict";
                    const {ownKeys: e} = Reflect
                      , t = ["toString", "toLocaleString", "valueOf"]
                      , r = (r, o) => {
                        const n = o[r];
                        if (!n)
                            return;
                        let c = !1;
                        try {
                            const e = Object.getOwnPropertyDescriptor(o, r);
                            e && (c = e.enumerable || !1)
                        } catch (e) {
                            console.warn(`Failed to get property descriptor for key "${r}":`, e)
                        }
                        globalThis.defineStrictProperty(r, n, o, c);
                        const s = n?.prototype;
                        if (s) {
                            const e = Object.getOwnPropertyDescriptors(s);
                            Object.keys(e).forEach((r => {
                                const o = e[r];
                                o && ( (e, r, o) => {
                                    if ("constructor" !== r && "value"in o && o.configurable && !t.includes(String(r))) {
                                        const {value: t, enumerable: n, get: c, set: s} = o
                                          , i = {
                                            enumerable: n,
                                            configurable: !1,
                                            ...t ? {
                                                value: t,
                                                writable: !1
                                            } : {
                                                get: c,
                                                set: s
                                            }
                                        };
                                        Object.defineProperty(e, r, i)
                                    }
                                }
                                )(s, r, o)
                            }
                            ))
                        }
                        e(n).forEach((e => {
                            const t = Object.getOwnPropertyDescriptor(n, e);
                            t && (t.writable || t.configurable) && globalThis.defineStrictProperty(e.toString(), n[e], n, t.enumerable)
                        }
                        ))
                    }
                      , o = e => "string" == typeof e ? decodeURIComponent(e).toLowerCase().trimStart() : e
                      , n = (e, t, r, o) => {
                        (e => e?.set && e?.get && "function" == typeof e.set && "function" == typeof e.get && !e.get.toString().includes("[native code]") && !e.set.toString().includes("[native code]"))(t) ? Object.defineProperty(r || globalThis, e, {
                            get: t.get,
                            set: t.set,
                            configurable: !1,
                            enumerable: o || !1
                        }) : Object.defineProperty(r || globalThis, e, {
                            value: t,
                            writable: !1,
                            configurable: !1,
                            enumerable: o || !1
                        })
                    }
                      , c = () => {
                        const e = globalThis.open
                          , t = document.open
                          , r = (t, r, o) => {
                            const n = "string" != typeof t
                              , c = e.call(window, t, r, o);
                            return n || ((s = t).startsWith("//") && /(?:[a-z0-9](?:[a-z0-9-]{0,61}[a-z0-9])?\.)+[a-z0-9][a-z0-9-]{0,61}[a-z0-9]/g.test(`${location.protocol}:${s}`) && (s = `${location.protocol}${s}`),
                            !s.startsWith("http") || new URL(s).hostname === location.hostname) ? {} : c;
                            var s
                        }
                        ;
                        defineStrictProperty("open", r, globalThis, !0),
                        defineStrictProperty("open", ( (e, o, n) => e ? r(e, o, n) : t.call(document, e, o, n)), document, !0)
                    }
                      , s = document.createElement
                      , i = (e, t) => {
                        const r = s.call(document, e, t)
                          , n = Element.prototype.setAttribute
                          , c = Element.prototype.setAttributeNS;
                        if ("iframe" === o(e)) {
                            globalThis.defineStrictProperty("srcdoc", {
                                get: () => {}
                                ,
                                set: () => {
                                    console.error("`srcdoc` is not allowed in iframe elements.")
                                }
                            }, r, !1);
                            const e = function(e, t) {
                                "srcdoc" !== e.toLowerCase() ? n.call(r, e, t) : console.error("`srcdoc` attribute is not allowed to be set.")
                            }
                              , t = function(e, t, o) {
                                "srcdoc" !== t.toLowerCase() ? c.call(r, e, t, o) : console.error("`srcdoc` attribute is not allowed to be set.")
                            };
                            r.setAttribute = e,
                            r.setAttributeNS = t
                        }
                        return r
                    }
                      , a = "client-binding"
                      , l = "security_overrideGlobals"
                      , d = ["/_api/v1/access-tokens", "/_api/v2/dynamicmodel"]
                      , u = e => (e instanceof Headers ? e.forEach(( (t, r) => {
                        decodeURIComponent(r).toLowerCase() === a && e.delete(r)
                    }
                    )) : Object.keys(e).forEach((t => {
                        decodeURIComponent(t).toLowerCase() === a && delete e[t]
                    }
                    )),
                    e)
                      , p = e => {
                        let t = !0;
                        const r = (e => {
                            let t, r;
                            if (globalThis.Request && e instanceof Request)
                                t = e.url;
                            else {
                                if ("function" != typeof e?.toString)
                                    throw new Error("Unsupported type for url");
                                t = e.toString()
                            }
                            try {
                                return new URL(t).pathname
                            } catch (e) {
                                return r = t.replace(/#.+/gi, "").split("?").shift(),
                                r.startsWith("/") ? r : `/${r}`
                            }
                        }
                        )(e)
                          , n = o(r);
                        return d.some((e => n.includes(e))) && (t = !1),
                        t
                    }
                      , f = (e=globalThis) => {
                        const t = fetch;
                        e.defineStrictProperty("fetch", (function() {
                            const r = (o = arguments,
                            globalThis.Request && o[0]instanceof Request && o[0]?.headers ? u(o[0].headers) : o[1]?.headers && u(o[1].headers),
                            o);
                            var o;
                            return p(arguments[0]) ? t.apply(e, Array.from(r)) : new Promise(( (e, t) => {
                                const r = new Error("TB002");
                                window.fedops?.reportError(r, l),
                                t(r)
                            }
                            ))
                        }
                        ))
                    }
                    ;
                    performance.mark("overrideGlobals started");
                    const {isExcludedFromSecurityExperiments: b, experiments: g} = window.viewerModel;
                    try {
                        ( (e=globalThis) => {
                            Object.defineProperty(e, "defineStrictProperty", {
                                value: n,
                                writable: !1,
                                enumerable: !1,
                                configurable: !1
                            })
                        }
                        )(),
                        c(),
                        g["specs.thunderbolt.hardenIFrames"] && !b && globalThis.defineStrictProperty("createElement", i, document, !0),
                        g["specs.thunderbolt.hardenFetchAndXHR"] && !b && (f(),
                        ( (e=globalThis) => {
                            const t = XMLHttpRequest;
                            e.defineStrictProperty("XMLHttpRequest", (function() {
                                const e = new t
                                  , r = e.open
                                  , o = e.setRequestHeader;
                                return e.open = function() {
                                    if (arguments.length < 2 || p(arguments[1]))
                                        return r.apply(e, Array.from(arguments));
                                    {
                                        const e = new Error("TB002");
                                        throw window.fedops?.reportError(e, l),
                                        e
                                    }
                                }
                                ,
                                e.setRequestHeader = function(t, r) {
                                    decodeURIComponent(t).toLowerCase() !== a && o.call(e, t, r)
                                }
                                ,
                                e
                            }
                            ))
                        }
                        )()),
                        g["specs.thunderbolt.removeServiceWorker"] && ( () => {
                            if (navigator && "serviceWorker"in navigator)
                                navigator.serviceWorker.register = () => console.log("Service worker registration is not allowed"),
                                Promise.resolve()
                        }
                        )(),
                        (e => {
                            let t = []
                              , o = [];
                            const {experiments: n} = window.viewerModel;
                            n["specs.thunderbolt.softFreeze_TextDecoder_TextEncoder"] && (o = o.concat(["TextEncoder", "TextDecoder"])),
                            n["specs.thunderbolt.hardenClientGlobals_EventTarget"] && n["specs.thunderbolt.moveSentryToHeadBeforeSecurityChanges"] && !e && (o = o.concat(["XMLHttpRequestEventTarget", "EventTarget"])),
                            n["specs.thunderbolt.hardenArray"] && o.push("Array"),
                            n["specs.thunderbolt.harden_URL_JSON"] && (o = o.concat(["URL", "JSON"])),
                            e || (t = t.concat(["addEventListener", "removeEventListener"])),
                            n["specs.thunderbolt.hardenEncodingDecoding"] && (t = t.concat(["encodeURI", "encodeURIComponent", "decodeURI", "decodeURIComponent"])),
                            n["specs.thunderbolt.hardenStringAndNumber"] && (o = o.concat(["String", "Number"])),
                            n["specs.thunderbolt.hardenObject"] && !e && o.push("Object"),
                            n["specs.thunderbolt.hardenReflect"] && (o = o.concat(["Reflect"])),
                            t.forEach((e => {
                                Object.freeze(globalThis[e]),
                                ["addEventListener", "removeEventListener"].includes(e) && globalThis.defineStrictProperty(e, document[e], document, !0),
                                globalThis.defineStrictProperty(e, globalThis[e], globalThis, !0)
                            }
                            )),
                            o.forEach((e => {
                                r(e, globalThis)
                            }
                            ))
                        }
                        )(b),
                        g["specs.thunderbolt.hardenTimeout"] && !b && (defineStrictProperty("preventStringArgument", ( (e, t, r) => {
                            const o = r || globalThis
                              , n = o[e];
                            defineStrictProperty(e, (function() {
                                const r = Array.from(arguments);
                                if ("string" != typeof r[t])
                                    return n.apply(o, r);
                                console.warn(`Calling ${e} with a String Argument at index ${t} is not allowed`)
                            }
                            ), o)
                        }
                        )),
                        preventStringArgument("setTimeout", 0),
                        preventStringArgument("setInterval", 0))
                    } catch (e) {
                        window?.viewerModel?.mode.debug && console.error(e);
                        const t = new Error("TB006");
                        window.fedops?.reportError(t, "security_overrideGlobals"),
                        window.Sentry ? window.Sentry.captureException(t) : globalThis.defineStrictProperty("sentryBuffer", [t], window, !1)
                    }
                    performance.mark("overrideGlobals ended")
                }
                )();
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/overrideGlobals.inline.45eeaad6.bundle.min.js.map
            </script>
            <script>
                window.commonConfig = viewerModel.commonConfig
            </script>
            <!-- Initial CSS -->
            <style data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/main.6c453198.min.css">
                @keyframes slide-horizontal-new {
                    0% {
                        transform: translateX(100%)
                    }
                }

                @keyframes slide-horizontal-old {
                    80% {
                        opacity: 1
                    }

                    to {
                        opacity: 0;
                        transform: translateX(-100%)
                    }
                }

                @keyframes slide-vertical-new {
                    0% {
                        transform: translateY(-100%)
                    }
                }

                @keyframes slide-vertical-old {
                    80% {
                        opacity: 1
                    }

                    to {
                        opacity: 0;
                        transform: translateY(100%)
                    }
                }

                @keyframes out-in-new {
                    0% {
                        opacity: 0
                    }
                }

                @keyframes out-in-old {
                    to {
                        opacity: 0
                    }
                }

                html[data-page-transition=SlideHorizontal]::view-transition-old(page-group) {
                    animation: slide-horizontal-old .6s cubic-bezier(.83,0,.17,1) forwards;
                    mix-blend-mode: normal
                }

                html[data-page-transition=SlideHorizontal]::view-transition-new(page-group) {
                    animation: slide-horizontal-new .6s cubic-bezier(.83,0,.17,1) backwards;
                    mix-blend-mode: normal
                }

                html[data-page-transition=SlideVertical]::view-transition-old(page-group) {
                    animation: slide-vertical-old .6s cubic-bezier(.83,0,.17,1) forwards;
                    mix-blend-mode: normal
                }

                html[data-page-transition=SlideVertical]::view-transition-new(page-group) {
                    animation: slide-vertical-new .6s cubic-bezier(.83,0,.17,1) backwards;
                    mix-blend-mode: normal
                }

                html[data-page-transition=OutIn]::view-transition-old(page-group) {
                    animation: out-in-old .35s cubic-bezier(.64,0,.78,0) forwards
                }

                html[data-page-transition=OutIn]::view-transition-new(page-group) {
                    animation: out-in-new .35s cubic-bezier(.22,1,.36,1) .35s backwards
                }

                @media(prefers-reduced-motion:reduce) {
                    ::view-transition-group(*),::view-transition-new(*),::view-transition-old(*) {
                        animation: none!important
                    }
                }

                body,html {
                    background: transparent;
                    border: 0;
                    margin: 0;
                    outline: 0;
                    padding: 0;
                    vertical-align: baseline
                }

                body {
                    --scrollbar-width: 0px;
                    font-family: Arial,Helvetica,sans-serif;
                    font-size: 10px
                }

                body,html {
                    height: 100%
                }

                body {
                    overflow-x: auto;
                    overflow-y: scroll
                }

                body:not(.responsive) #site-root {
                    min-width: var(--site-width);
                    width: 100%
                }

                body:not([data-js-loaded]) [data-hide-prejs] {
                    visibility: hidden
                }

                #SITE_CONTAINER {
                    position: relative
                }

                :root {
                    --one-unit: 1vw;
                    --section-max-width: 9999px
                }

                @supports(-webkit-appearance: none) and (stroke-color:transparent) {
                    :root {
                        --safari-sticky-fix:opacity
                    }
                }

                @supports(container-type:inline-size) {
                    :root {
                        --one-unit: 1cqw
                    }
                }

                [id^=oldHoverBox-] {
                    mix-blend-mode: plus-lighter;
                    transition: opacity .5s ease,visibility .5s ease
                }

                [data-mesh-id$=inlineContent-gridContainer]:has(>[id^=oldHoverBox-]) {
                    isolation: isolate
                }
            </style>
            <style data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/main.renderer.beea92dc.min.css">
                a,abbr,acronym,address,applet,b,big,blockquote,button,caption,center,cite,code,dd,del,dfn,div,dl,dt,em,fieldset,font,footer,form,h1,h2,h3,h4,h5,h6,header,i,iframe,img,ins,kbd,label,legend,li,nav,object,ol,p,pre,q,s,samp,section,small,span,strike,strong,sub,sup,table,tbody,td,tfoot,th,thead,title,tr,tt,u,ul,var {
                    background: transparent;
                    border: 0;
                    margin: 0;
                    outline: 0;
                    padding: 0;
                    vertical-align: baseline
                }

                input,select,textarea {
                    box-sizing: border-box;
                    font-family: Helvetica,Arial,sans-serif
                }

                ol,ul {
                    list-style: none
                }

                blockquote,q {
                    quotes: none
                }

                ins {
                    text-decoration: none
                }

                del {
                    text-decoration: line-through
                }

                table {
                    border-collapse: collapse;
                    border-spacing: 0
                }

                a {
                    cursor: pointer;
                    text-decoration: none
                }

                .testStyles {
                    overflow-y: hidden
                }

                .reset-button {
                    -webkit-appearance: none;
                    background: none;
                    border: 0;
                    color: inherit;
                    font: inherit;
                    line-height: normal;
                    outline: 0;
                    overflow: visible;
                    padding: 0;
                    -webkit-user-select: none;
                    -moz-user-select: none;
                    -ms-user-select: none
                }

                :focus {
                    outline: none
                }

                body.device-mobile-optimized:not(.disable-site-overflow) {
                    overflow-x: hidden;
                    overflow-y: scroll
                }

                body.device-mobile-optimized:not(.responsive) #SITE_CONTAINER {
                    margin-left: auto;
                    margin-right: auto;
                    overflow-x: visible;
                    position: relative;
                    width: 320px
                }

                body.device-mobile-optimized:not(.responsive):not(.blockSiteScrolling) #SITE_CONTAINER {
                    margin-top: 0
                }

                body.device-mobile-optimized>* {
                    max-width: 100%!important
                }

                body.device-mobile-optimized #site-root {
                    overflow-x: hidden;
                    overflow-y: hidden
                }

                @supports(overflow: clip) {
                    body.device-mobile-optimized #site-root {
                        overflow-x:clip;
                        overflow-y: clip
                    }
                }

                body.device-mobile-non-optimized #SITE_CONTAINER #site-root:not(.overflow-clip-in-mobile) {
                    overflow-x: hidden;
                    overflow-y: auto
                }

                body.device-mobile-non-optimized #SITE_CONTAINER #site-root.overflow-clip-in-mobile {
                    overflow-x: clip;
                    overflow-y: clip
                }

                body.device-mobile-non-optimized.fullScreenMode {
                    background-color: #5f6360
                }

                body.device-mobile-non-optimized.fullScreenMode #MOBILE_ACTIONS_MENU,body.device-mobile-non-optimized.fullScreenMode #SITE_BACKGROUND,body.device-mobile-non-optimized.fullScreenMode #site-root,body.fullScreenMode #WIX_ADS {
                    visibility: hidden
                }

                body.fullScreenMode {
                    overflow-x: hidden!important;
                    overflow-y: hidden!important
                }

                body.fullScreenMode.device-mobile-optimized #TINY_MENU {
                    opacity: 0;
                    pointer-events: none
                }

                body.fullScreenMode-scrollable.device-mobile-optimized {
                    overflow-x: hidden!important;
                    overflow-y: auto!important
                }

                body.fullScreenMode-scrollable.device-mobile-optimized #masterPage,body.fullScreenMode-scrollable.device-mobile-optimized #site-root {
                    overflow-x: hidden!important;
                    overflow-y: hidden!important
                }

                body.fullScreenMode-scrollable.device-mobile-optimized #SITE_BACKGROUND,body.fullScreenMode-scrollable.device-mobile-optimized #masterPage {
                    height: auto!important
                }

                body.fullScreenMode-scrollable.device-mobile-optimized #masterPage.mesh-layout {
                    height: 0!important
                }

                body.blockSiteScrolling,body.siteScrollingBlocked {
                    position: fixed;
                    width: 100%
                }

                body.blockSiteScrolling #SITE_CONTAINER {
                    margin-top: calc(var(--blocked-site-scroll-margin-top)*-1)
                }

                body.blockSiteScrolling:not(.responsive) #WIX_ADS {
                    margin-top: var(--blocked-site-scroll-margin-top)
                }

                #site-root {
                    margin: 0 auto;
                    min-height: 100%;
                    position: relative;
                    top: var(--wix-ads-height)
                }

                #site-root img:not([src]) {
                    visibility: hidden
                }

                #site-root svg img:not([src]) {
                    visibility: visible
                }

                .auto-generated-link {
                    color: inherit
                }

                #SCROLL_TO_BOTTOM,#SCROLL_TO_TOP {
                    height: 0
                }

                .has-click-trigger {
                    cursor: pointer
                }

                .fullScreenOverlay {
                    bottom: 0;
                    display: flex;
                    justify-content: center;
                    left: 0;
                    overflow-y: hidden;
                    position: fixed;
                    right: 0;
                    top: -60px;
                    z-index: 1005
                }

                .fullScreenOverlay>.fullScreenOverlayContent {
                    bottom: 0;
                    left: 0;
                    margin: 0 auto;
                    overflow: hidden;
                    position: absolute;
                    right: 0;
                    top: 60px;
                    transform: translateZ(0)
                }

                [data-mesh-id$=centeredContent],[data-mesh-id$=form],[data-mesh-id$=inlineContent] {
                    pointer-events: none;
                    position: relative
                }

                [data-mesh-id$=-gridWrapper],[data-mesh-id$=-rotated-wrapper] {
                    pointer-events: none
                }

                [data-mesh-id$=-gridContainer]>*,[data-mesh-id$=-rotated-wrapper]>*,[data-mesh-id$=inlineContent]>:not([data-mesh-id$=-gridContainer]) {
                    pointer-events: auto
                }

                .device-mobile-optimized #masterPage.mesh-layout #SOSP_CONTAINER_CUSTOM_ID {
                    grid-area: 2/1/3/2;
                    -ms-grid-row: 2;
                    position: relative
                }

                #masterPage.mesh-layout {
                    -ms-grid-rows: max-content max-content min-content max-content;
                    -ms-grid-columns: 100%;
                    align-items: start;
                    display: -ms-grid;
                    display: grid;
                    grid-template-columns: 100%;
                    grid-template-rows: max-content max-content min-content max-content;
                    justify-content: stretch
                }

                #masterPage.mesh-layout #PAGES_CONTAINER,#masterPage.mesh-layout #SITE_FOOTER-placeholder,#masterPage.mesh-layout #SITE_FOOTER_WRAPPER,#masterPage.mesh-layout #SITE_HEADER-placeholder,#masterPage.mesh-layout #SITE_HEADER_WRAPPER,#masterPage.mesh-layout #SOSP_CONTAINER_CUSTOM_ID[data-state~=mobileView],#masterPage.mesh-layout #soapAfterPagesContainer,#masterPage.mesh-layout #soapBeforePagesContainer {
                    -ms-grid-row-align: start;
                    -ms-grid-column-align: start;
                    -ms-grid-column: 1
                }

                #masterPage.mesh-layout #SITE_HEADER-placeholder,#masterPage.mesh-layout #SITE_HEADER_WRAPPER {
                    grid-area: 1/1/2/2;
                    -ms-grid-row: 1
                }

                #masterPage.mesh-layout #PAGES_CONTAINER,#masterPage.mesh-layout #soapAfterPagesContainer,#masterPage.mesh-layout #soapBeforePagesContainer {
                    grid-area: 3/1/4/2;
                    -ms-grid-row: 3
                }

                #masterPage.mesh-layout #soapAfterPagesContainer,#masterPage.mesh-layout #soapBeforePagesContainer {
                    width: 100%
                }

                #masterPage.mesh-layout #PAGES_CONTAINER {
                    align-self: stretch
                }

                #masterPage.mesh-layout main#PAGES_CONTAINER {
                    display: block
                }

                #masterPage.mesh-layout #SITE_FOOTER-placeholder,#masterPage.mesh-layout #SITE_FOOTER_WRAPPER {
                    grid-area: 4/1/5/2;
                    -ms-grid-row: 4
                }

                #masterPage.mesh-layout #SITE_PAGES,#masterPage.mesh-layout [data-mesh-id=PAGES_CONTAINERcenteredContent],#masterPage.mesh-layout [data-mesh-id=PAGES_CONTAINERinlineContent] {
                    height: 100%
                }

                #masterPage.mesh-layout.desktop>* {
                    width: 100%
                }

                #masterPage.mesh-layout #PAGES_CONTAINER,#masterPage.mesh-layout #SITE_FOOTER_WRAPPER,#masterPage.mesh-layout #SITE_HEADER_WRAPPER,#masterPage.mesh-layout #SITE_PAGES,#masterPage.mesh-layout #masterPageinlineContent,#masterPage.mesh-layout:not(.one-doc) #SITE_FOOTER,#masterPage.mesh-layout:not(.one-doc) #SITE_HEADER {
                    position: relative
                }

                #masterPage.mesh-layout #SITE_HEADER {
                    grid-area: 1/1/2/2
                }

                #masterPage.mesh-layout #SITE_FOOTER {
                    grid-area: 4/1/5/2
                }

                #masterPage.mesh-layout.overflow-x-clip #SITE_FOOTER,#masterPage.mesh-layout.overflow-x-clip #SITE_HEADER {
                    overflow-x: clip
                }

                [data-z-counter] {
                    z-index: 0
                }

                [data-z-counter="0"] {
                    z-index: auto
                }

                .wixSiteProperties {
                    -webkit-font-smoothing: antialiased;
                    -moz-osx-font-smoothing: grayscale
                }

                :root {
                    --wst-button-color-fill-primary: rgb(var(--color_48));
                    --wst-button-color-border-primary: rgb(var(--color_49));
                    --wst-button-color-text-primary: rgb(var(--color_50));
                    --wst-button-color-fill-primary-hover: rgb(var(--color_51));
                    --wst-button-color-border-primary-hover: rgb(var(--color_52));
                    --wst-button-color-text-primary-hover: rgb(var(--color_53));
                    --wst-button-color-fill-primary-disabled: rgb(var(--color_54));
                    --wst-button-color-border-primary-disabled: rgb(var(--color_55));
                    --wst-button-color-text-primary-disabled: rgb(var(--color_56));
                    --wst-button-color-fill-secondary: rgb(var(--color_57));
                    --wst-button-color-border-secondary: rgb(var(--color_58));
                    --wst-button-color-text-secondary: rgb(var(--color_59));
                    --wst-button-color-fill-secondary-hover: rgb(var(--color_60));
                    --wst-button-color-border-secondary-hover: rgb(var(--color_61));
                    --wst-button-color-text-secondary-hover: rgb(var(--color_62));
                    --wst-button-color-fill-secondary-disabled: rgb(var(--color_63));
                    --wst-button-color-border-secondary-disabled: rgb(var(--color_64));
                    --wst-button-color-text-secondary-disabled: rgb(var(--color_65));
                    --wst-color-fill-base-1: rgb(var(--color_36));
                    --wst-color-fill-base-2: rgb(var(--color_37));
                    --wst-color-fill-base-shade-1: rgb(var(--color_38));
                    --wst-color-fill-base-shade-2: rgb(var(--color_39));
                    --wst-color-fill-base-shade-3: rgb(var(--color_40));
                    --wst-color-fill-accent-1: rgb(var(--color_41));
                    --wst-color-fill-accent-2: rgb(var(--color_42));
                    --wst-color-fill-accent-3: rgb(var(--color_43));
                    --wst-color-fill-accent-4: rgb(var(--color_44));
                    --wst-color-fill-background-primary: rgb(var(--color_11));
                    --wst-color-fill-background-secondary: rgb(var(--color_12));
                    --wst-color-text-primary: rgb(var(--color_15));
                    --wst-color-text-secondary: rgb(var(--color_14));
                    --wst-color-action: rgb(var(--color_18));
                    --wst-color-disabled: rgb(var(--color_39));
                    --wst-color-title: rgb(var(--color_45));
                    --wst-color-subtitle: rgb(var(--color_46));
                    --wst-color-line: rgb(var(--color_47));
                    --wst-font-style-h2: var(--font_2);
                    --wst-font-style-h3: var(--font_3);
                    --wst-font-style-h4: var(--font_4);
                    --wst-font-style-h5: var(--font_5);
                    --wst-font-style-h6: var(--font_6);
                    --wst-font-style-body-large: var(--font_7);
                    --wst-font-style-body-medium: var(--font_8);
                    --wst-font-style-body-small: var(--font_9);
                    --wst-font-style-body-x-small: var(--font_10);
                    --wst-color-custom-1: rgb(var(--color_13));
                    --wst-color-custom-2: rgb(var(--color_16));
                    --wst-color-custom-3: rgb(var(--color_17));
                    --wst-color-custom-4: rgb(var(--color_19));
                    --wst-color-custom-5: rgb(var(--color_20));
                    --wst-color-custom-6: rgb(var(--color_21));
                    --wst-color-custom-7: rgb(var(--color_22));
                    --wst-color-custom-8: rgb(var(--color_23));
                    --wst-color-custom-9: rgb(var(--color_24));
                    --wst-color-custom-10: rgb(var(--color_25));
                    --wst-color-custom-11: rgb(var(--color_26));
                    --wst-color-custom-12: rgb(var(--color_27));
                    --wst-color-custom-13: rgb(var(--color_28));
                    --wst-color-custom-14: rgb(var(--color_29));
                    --wst-color-custom-15: rgb(var(--color_30));
                    --wst-color-custom-16: rgb(var(--color_31));
                    --wst-color-custom-17: rgb(var(--color_32));
                    --wst-color-custom-18: rgb(var(--color_33));
                    --wst-color-custom-19: rgb(var(--color_34));
                    --wst-color-custom-20: rgb(var(--color_35))
                }
            </style>
            <meta name="format-detection" content="telephone=no">
            <meta name="skype_toolbar" content="skype_toolbar_parser_compatible">
            <!--pageHtmlEmbeds.head start-->
            <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.head start"></script>
            <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.head end"></script>
            <!--pageHtmlEmbeds.head end-->
            <!-- head performance data start -->
            <!-- head performance data end -->
            <meta http-equiv="X-Wix-Meta-Site-Id" content="736c7394-4e87-4a3c-9265-7dad8dc29df5">
            <meta http-equiv="X-Wix-Application-Instance-Id" content="2538b395-fb67-480b-aef2-fd071e6b62dd">
            <meta http-equiv="X-Wix-Published-Version" content="28"/>
            <meta http-equiv="etag" content="bug"/>
            <!-- render-head end -->
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[FiveGridLine_SolidLine].23b2f23d.min.css">
                .aVng1S {
                    border-top: var(--lnw,2px) solid rgba(var(--brd,var(--color_15,color_15)),var(--alpha-brd,1));
                    box-sizing: border-box;
                    height: 0
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt_bootstrap.d8597a4d.min.css">
                .J6KGih {
                    cursor: pointer
                }

                .sNF2R0 {
                    opacity: 0
                }

                .hLoBV3 {
                    transition: opacity var(--transition-duration) cubic-bezier(.37,0,.63,1)
                }

                .Rdf41z,.hLoBV3 {
                    opacity: 1
                }

                .ftlZWo {
                    transition: opacity var(--transition-duration) cubic-bezier(.37,0,.63,1)
                }

                .ATGlOr,.ftlZWo {
                    opacity: 0
                }

                .KQSXD0 {
                    transition: opacity var(--transition-duration) cubic-bezier(.64,0,.78,0)
                }

                .KQSXD0,.pagQKE {
                    opacity: 1
                }

                ._6zG5H {
                    opacity: 0;
                    transition: opacity var(--transition-duration) cubic-bezier(.22,1,.36,1)
                }

                .BB49uC {
                    transform: translateX(100%)
                }

                .j9xE1V {
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .ICs7Rs,.j9xE1V {
                    transform: translateX(0)
                }

                .DxijZJ {
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .B5kjYq,.DxijZJ {
                    transform: translateX(-100%)
                }

                .cJijIV {
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .cJijIV,.hOxaWM {
                    transform: translateX(0)
                }

                .T9p3fN {
                    transform: translateX(100%);
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .qDxYJm {
                    transform: translateY(100%)
                }

                .aA9V0P {
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .YPXPAS,.aA9V0P {
                    transform: translateY(0)
                }

                .Xf2zsA {
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .Xf2zsA,.y7Kt7s {
                    transform: translateY(-100%)
                }

                .EeUgMu {
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                .EeUgMu,.fdHrtm {
                    transform: translateY(0)
                }

                .WIFaG4 {
                    transform: translateY(100%);
                    transition: transform var(--transition-duration) cubic-bezier(.87,0,.13,1)
                }

                body:not(.responsive) .JsJXaX {
                    overflow-x: clip
                }

                [data-view-transition=page-transition] .JsJXaX {
                    view-transition-name: page-group
                }

                .AnQkDU {
                    display: grid;
                    grid-template-columns: 1fr;
                    grid-template-rows: 1fr;
                    height: 100%
                }

                .AnQkDU>div {
                    align-self: stretch!important;
                    grid-area: 1/1/2/2;
                    justify-self: stretch!important
                }

                .StylableButton2545352419__root {
                    -archetype: box;
                    border: none;
                    box-sizing: border-box;
                    cursor: pointer;
                    display: block;
                    height: 100%;
                    min-height: 10px;
                    min-width: 10px;
                    padding: 0;
                    touch-action: manipulation;
                    width: 100%
                }

                .StylableButton2545352419__root[disabled] {
                    pointer-events: none
                }

                .StylableButton2545352419__root:not(:hover):not([disabled]).StylableButton2545352419--hasBackgroundColor {
                    background-color: var(--corvid-background-color)!important
                }

                .StylableButton2545352419__root:hover:not([disabled]).StylableButton2545352419--hasHoverBackgroundColor {
                    background-color: var(--corvid-hover-background-color)!important
                }

                .StylableButton2545352419__root:not(:hover)[disabled].StylableButton2545352419--hasDisabledBackgroundColor {
                    background-color: var(--corvid-disabled-background-color)!important
                }

                .StylableButton2545352419__root:not(:hover):not([disabled]).StylableButton2545352419--hasBorderColor {
                    border-color: var(--corvid-border-color)!important
                }

                .StylableButton2545352419__root:hover:not([disabled]).StylableButton2545352419--hasHoverBorderColor {
                    border-color: var(--corvid-hover-border-color)!important
                }

                .StylableButton2545352419__root:not(:hover)[disabled].StylableButton2545352419--hasDisabledBorderColor {
                    border-color: var(--corvid-disabled-border-color)!important
                }

                .StylableButton2545352419__root.StylableButton2545352419--hasBorderRadius {
                    border-radius: var(--corvid-border-radius)!important
                }

                .StylableButton2545352419__root.StylableButton2545352419--hasBorderWidth {
                    border-width: var(--corvid-border-width)!important
                }

                .StylableButton2545352419__root:not(:hover):not([disabled]).StylableButton2545352419--hasColor,.StylableButton2545352419__root: not(:hover):not([disabled]).StylableButton2545352419--hasColor .StylableButton2545352419__label {
                    color:var(--corvid-color)!important
                }

                .StylableButton2545352419__root:hover:not([disabled]).StylableButton2545352419--hasHoverColor,.StylableButton2545352419__root: hover:not([disabled]).StylableButton2545352419--hasHoverColor .StylableButton2545352419__label {
                    color:var(--corvid-hover-color)!important
                }

                .StylableButton2545352419__root:not(:hover)[disabled].StylableButton2545352419--hasDisabledColor,.StylableButton2545352419__root: not(:hover)[disabled].StylableButton2545352419--hasDisabledColor .StylableButton2545352419__label {
                    color:var(--corvid-disabled-color)!important
                }

                .StylableButton2545352419__link {
                    -archetype: box;
                    box-sizing: border-box;
                    color: #000;
                    text-decoration: none
                }

                .StylableButton2545352419__container {
                    align-items: center;
                    display: flex;
                    flex-basis: auto;
                    flex-direction: row;
                    flex-grow: 1;
                    height: 100%;
                    justify-content: center;
                    overflow: hidden;
                    transition: all .2s ease,visibility 0s;
                    width: 100%
                }

                .StylableButton2545352419__label {
                    -archetype: text;
                    -controller-part-type: LayoutChildDisplayDropdown,LayoutFlexChildSpacing(first);
                    max-width: 100%;
                    min-width: 1.8em;
                    overflow: hidden;
                    text-align: center;
                    text-overflow: ellipsis;
                    transition: inherit;
                    white-space: nowrap
                }

                .StylableButton2545352419__root.StylableButton2545352419--isMaxContent .StylableButton2545352419__label {
                    text-overflow: unset
                }

                .StylableButton2545352419__root.StylableButton2545352419--isWrapText .StylableButton2545352419__label {
                    min-width: 10px;
                    overflow-wrap: break-word;
                    white-space: break-spaces;
                    word-break: break-word
                }

                .StylableButton2545352419__icon {
                    -archetype: icon;
                    -controller-part-type: LayoutChildDisplayDropdown,LayoutFlexChildSpacing(last);
                    flex-shrink: 0;
                    height: 50px;
                    min-width: 1px;
                    transition: inherit
                }

                .StylableButton2545352419__icon.StylableButton2545352419--override {
                    display: block!important
                }

                .StylableButton2545352419__icon svg,.StylableButton2545352419__icon>span {
                    display: flex;
                    height: inherit;
                    width: inherit
                }

                .StylableButton2545352419__root:not(:hover):not([disalbed]).StylableButton2545352419--hasIconColor .StylableButton2545352419__icon svg {
                    fill: var(--corvid-icon-color)!important;
                    stroke: var(--corvid-icon-color)!important
                }

                .StylableButton2545352419__root:hover:not([disabled]).StylableButton2545352419--hasHoverIconColor .StylableButton2545352419__icon svg {
                    fill: var(--corvid-hover-icon-color)!important;
                    stroke: var(--corvid-hover-icon-color)!important
                }

                .StylableButton2545352419__root:not(:hover)[disabled].StylableButton2545352419--hasDisabledIconColor .StylableButton2545352419__icon svg {
                    fill: var(--corvid-disabled-icon-color)!important;
                    stroke: var(--corvid-disabled-icon-color)!important
                }

                .a9YhBi {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .dX12nb {
                    cursor: pointer
                }

                .AKxYR5 {
                    -webkit-tap-highlight-color: rgba(0,0,0,0);
                    fill: var(--corvid-fill-color,var(--fill));
                    fill-opacity: var(--fill-opacity);
                    stroke: var(--corvid-stroke-color,var(--stroke));
                    stroke-opacity: var(--stroke-opacity);
                    stroke-width: var(--stroke-width);
                    filter: var(--drop-shadow,none);
                    opacity: var(--opacity);
                    transform: var(--flip)
                }

                .AKxYR5,.AKxYR5 svg {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .AKxYR5 svg {
                    height: var(--svg-calculated-height,100%);
                    margin: auto;
                    padding: var(--svg-calculated-padding,0);
                    width: var(--svg-calculated-width,100%)
                }

                .AKxYR5 svg: not([data-type=ugc]) {
                    overflow:visible
                }

                .VZYmYf * {
                    vector-effect: non-scaling-stroke
                }

                .HcOXKn {
                    -webkit-text-size-adjust: 100%;
                    -moz-text-size-adjust: 100%;
                    text-size-adjust: 100%
                }

                ol.font_100,ul.font_100 {
                    color: #080808;
                    font-family: "Arial, Helvetica, sans-serif",serif;
                    font-size: 10px;
                    font-style: normal;
                    font-variant: normal;
                    font-weight: 400;
                    letter-spacing: normal;
                    line-height: normal;
                    margin: 0;
                    text-decoration: none
                }

                ol.font_100 li,ul.font_100 li {
                    margin-bottom: 12px
                }

                ol.wix-list-text-align,ul.wix-list-text-align {
                    list-style-position: inside
                }

                ol.wix-list-text-align h1,ol.wix-list-text-align h2,ol.wix-list-text-align h3,ol.wix-list-text-align h4,ol.wix-list-text-align h5,ol.wix-list-text-align h6,ol.wix-list-text-align p,ul.wix-list-text-align h1,ul.wix-list-text-align h2,ul.wix-list-text-align h3,ul.wix-list-text-align h4,ul.wix-list-text-align h5,ul.wix-list-text-align h6,ul.wix-list-text-align p {
                    display: inline
                }

                .ONIxfn {
                    cursor: pointer
                }

                .WUKwEB {
                    clip: rect(0 0 0 0);
                    border: 0;
                    height: 1px;
                    margin: -1px;
                    overflow: hidden;
                    padding: 0;
                    position: absolute;
                    width: 1px
                }

                .QxJLC3 [data-attr-richtext-marker=true] {
                    display: block
                }

                .QxJLC3 [data-attr-richtext-marker=true] table {
                    border-collapse: collapse;
                    margin: 15px 0;
                    width: 100%
                }

                .QxJLC3 [data-attr-richtext-marker=true] table td {
                    padding: 12px;
                    position: relative
                }

                .QxJLC3 [data-attr-richtext-marker=true] table td: after {
                    border-bottom:1px solid currentColor;
                    border-left: 1px solid currentColor;
                    bottom: 0;
                    content: "";
                    left: 0;
                    opacity: .2;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .QxJLC3 [data-attr-richtext-marker=true] table tr td: last-child:after {
                    border-right:1px solid currentColor
                }

                .QxJLC3 [data-attr-richtext-marker=true] table tr: first-child td:after {
                    border-top:1px solid currentColor
                }

                @supports(-webkit-appearance: none) and (stroke-color:transparent) {
                    .lq2cno>*>:first-child {
                        vertical-align:top
                    }
                }

                @supports(-webkit-touch-callout:none) {
                    .lq2cno>*>:first-child {
                        vertical-align: top
                    }
                }

                .agLt0N :is(p,h1,h2,h3,h4,h5,h6,ul,ol,span[data-attr-richtext-marker],blockquote) [class$=rich-text__text],.agLt0N : is(p,h1,h2,h3,h4,h5,h6,ul,ol,span[data-attr-richtext-marker],blockquote)[class$=rich-text__text] {
                    color:var(--corvid-color,currentColor)
                }

                .agLt0N :is(p,h1,h2,h3,h4,h5,h6,ul,ol,span[data-attr-richtext-marker],blockquote) span[style*=color] {
                    color: var(--corvid-color,currentColor)!important
                }

                .uGVkMG {
                    direction: var(--text-direction);
                    min-height: var(--min-height);
                    min-width: var(--min-width)
                }

                .uGVkMG .edKzOf {
                    word-wrap: break-word;
                    height: 100%;
                    overflow-wrap: break-word;
                    position: relative;
                    width: 100%
                }

                .uGVkMG .edKzOf ul {
                    list-style: disc inside
                }

                .uGVkMG .edKzOf li {
                    margin-bottom: 12px
                }

                .SxM0TO blockquote,.SxM0TO h1,.SxM0TO h2,.SxM0TO h3,.SxM0TO h4,.SxM0TO h5,.SxM0TO h6,.SxM0TO p {
                    letter-spacing: normal;
                    line-height: normal
                }

                .nJYhU3 {
                    min-height: var(--min-height);
                    min-width: var(--min-width)
                }

                .nJYhU3 .edKzOf {
                    word-wrap: break-word;
                    height: 100%;
                    overflow-wrap: break-word;
                    position: relative;
                    width: 100%
                }

                .nJYhU3 .edKzOf ol,.nJYhU3 .edKzOf ul {
                    letter-spacing: normal;
                    line-height: normal;
                    margin-inline-start:.5em;padding-inline-start:1.3em}

                .nJYhU3 .edKzOf ul {
                    list-style-type: disc
                }

                .nJYhU3 .edKzOf ol {
                    list-style-type: decimal
                }

                .nJYhU3 .edKzOf ol ul,.nJYhU3 .edKzOf ul ul {
                    line-height: normal;
                    list-style-type: circle
                }

                .nJYhU3 .edKzOf ol ol ul,.nJYhU3 .edKzOf ol ul ul,.nJYhU3 .edKzOf ul ol ul,.nJYhU3 .edKzOf ul ul ul {
                    line-height: normal;
                    list-style-type: square
                }

                .nJYhU3 .edKzOf li {
                    font-style: inherit;
                    font-weight: inherit;
                    letter-spacing: normal;
                    line-height: inherit
                }

                .nJYhU3 .edKzOf h1,.nJYhU3 .edKzOf h2,.nJYhU3 .edKzOf h3,.nJYhU3 .edKzOf h4,.nJYhU3 .edKzOf h5,.nJYhU3 .edKzOf h6,.nJYhU3 .edKzOf p {
                    letter-spacing: normal;
                    line-height: normal;
                    margin-block:0;margin: 0
                }

                .nJYhU3 .edKzOf a {
                    color: inherit
                }

                .SxM0TO,.c9GqVL {
                    word-wrap: break-word;
                    direction: var(--text-direction);
                    min-height: var(--min-height);
                    min-width: var(--min-width);
                    mix-blend-mode: var(--blendMode,normal);
                    overflow-wrap: break-word;
                    pointer-events: none;
                    text-align: start;
                    text-shadow: var(--textOutline,0 0 transparent),var(--textShadow,0 0 transparent);
                    text-transform: var(--textTransform,"none")
                }

                .SxM0TO>*,.c9GqVL>* {
                    pointer-events: auto
                }

                .SxM0TO li,.c9GqVL li {
                    font-style: inherit;
                    font-weight: inherit;
                    letter-spacing: normal;
                    line-height: inherit
                }

                .SxM0TO ol,.SxM0TO ul,.c9GqVL ol,.c9GqVL ul {
                    letter-spacing: normal;
                    line-height: normal;
                    margin-inline-end:0;margin-inline-start:.5em}

                .SxM0TO:not(.YQcXTT) ol,.SxM0TO: not(.YQcXTT) ul,.c9GqVL:not(.YQcXTT) ol,.c9GqVL:not(.YQcXTT) ul {
                    padding-inline-end:0;
                    padding-inline-start:1.3em}

                .SxM0TO ul,.c9GqVL ul {
                    list-style-type: disc
                }

                .SxM0TO ol,.c9GqVL ol {
                    list-style-type: decimal
                }

                .SxM0TO ol ul,.SxM0TO ul ul,.c9GqVL ol ul,.c9GqVL ul ul {
                    list-style-type: circle
                }

                .SxM0TO ol ol ul,.SxM0TO ol ul ul,.SxM0TO ul ol ul,.SxM0TO ul ul ul,.c9GqVL ol ol ul,.c9GqVL ol ul ul,.c9GqVL ul ol ul,.c9GqVL ul ul ul {
                    list-style-type: square
                }

                .SxM0TO blockquote,.SxM0TO h1,.SxM0TO h2,.SxM0TO h3,.SxM0TO h4,.SxM0TO h5,.SxM0TO h6,.SxM0TO p,.c9GqVL blockquote,.c9GqVL h1,.c9GqVL h2,.c9GqVL h3,.c9GqVL h4,.c9GqVL h5,.c9GqVL h6,.c9GqVL p {
                    margin-block: 0;
                    margin: 0
                }

                .SxM0TO a,.c9GqVL a {
                    color: inherit
                }

                .YQcXTT li {
                    margin-inline-end: 0;
                    margin-inline-start:1.3em}

                .Vd6aQZ {
                    overflow: hidden;
                    padding: 0;
                    pointer-events: none;
                    white-space: nowrap
                }

                .mHZSwn {
                    display: none
                }

                .lvxhkV {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0;
                    width: 100%
                }

                .QJjwEo {
                    transform: translateY(-100%);
                    transition: .2s ease-in
                }

                .kdBXfh {
                    transition: .2s
                }

                .MP52zt {
                    opacity: 0;
                    transition: .2s ease-in
                }

                .MP52zt.Bhu9m5 {
                    z-index: -1!important
                }

                .LVP8Wf {
                    opacity: 1;
                    transition: .2s
                }

                .VrZrC0 {
                    height: auto
                }

                .VrZrC0,.cKxVkc {
                    position: relative;
                    width: 100%
                }

                :host(:not(.device-mobile-optimized)) .vlM3HR,body: not(.device-mobile-optimized) .vlM3HR {
                    margin-left:calc((100% - var(--site-width))/2);
                    width: var(--site-width)
                }

                .AT7o0U[data-focuscycled=active] {
                    outline: 1px solid transparent
                }

                .AT7o0U[data-focuscycled=active]: not(:focus-within) {
                    outline:2px solid transparent;
                    transition: outline .01s ease
                }

                .AT7o0U .vlM3HR {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .HlRz5e {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .HlRz5e img {
                    max-width: var(--wix-img-max-width,100%)
                }

                .HlRz5e[data-animate-blur] img {
                    filter: blur(9px);
                    transition: filter .8s ease-in
                }

                .HlRz5e[data-animate-blur] img[data-load-done] {
                    filter: none
                }

                .I5zqsT {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .WzbAF8 .mpGTIt .O6KwRn {
                    display: var(--item-display);
                    height: var(--item-size);
                    margin: var(--item-margin);
                    width: var(--item-size)
                }

                .WzbAF8 .mpGTIt .O6KwRn:last-child {
                    margin: 0
                }

                .WzbAF8 .mpGTIt .O6KwRn .oRtuWN {
                    display: block
                }

                .WzbAF8 .mpGTIt .O6KwRn .oRtuWN .YaS0jR {
                    height: var(--item-size);
                    width: var(--item-size)
                }

                .WzbAF8 .mpGTIt {
                    height: 100%;
                    position: absolute;
                    white-space: nowrap;
                    width: 100%
                }

                :host(.device-mobile-optimized) .WzbAF8 .mpGTIt,body.device-mobile-optimized .WzbAF8 .mpGTIt {
                    white-space: normal
                }

                .big2ZD {
                    display: grid;
                    grid-template-columns: 1fr;
                    grid-template-rows: 1fr;
                    height: calc(100% - var(--wix-ads-height));
                    left: 0;
                    margin-top: var(--wix-ads-height);
                    position: fixed;
                    top: 0;
                    width: 100%
                }

                .SHHiV9,.big2ZD {
                    pointer-events: none;
                    z-index: var(--pinned-layer-in-container,var(--above-all-in-container))
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[DropDownMenu_TextSeparatorsMenuButtonSkin].a3334fed.min.css">
                .EFUBGn,.rhHoTC {
                    box-sizing: border-box;
                    height: 100%;
                    overflow: visible;
                    position: relative;
                    width: auto
                }

                .EFUBGn[data-state~=header] a,.EFUBGn[data-state~=header] div,[data-state~=header].rhHoTC a,[data-state~=header].rhHoTC div {
                    cursor: default!important
                }

                .EFUBGn .wIGMae,.rhHoTC .wIGMae {
                    display: inline-block;
                    height: 100%;
                    width: 100%
                }

                .rhHoTC {
                    --display: inline-block;
                    border-left: 1px solid rgba(var(--sep,var(--color_15,color_15)),var(--alpha-sep,1));
                    cursor: pointer;
                    display: var(--display);
                    font: var(--fnt,var(--font_1))
                }

                .rhHoTC .aWTgIN {
                    color: rgb(var(--txt,var(--color_15,color_15)));
                    display: inline-block;
                    padding: 0 10px;
                    transition: var(--trans,color .4s ease 0s)
                }

                .rhHoTC .Zw7XIs {
                    padding: 0 var(--pad,5px)
                }

                .rhHoTC:first-child[data-direction=ltr],.rhHoTC:last-child[data-direction=rtl],.rhHoTC[data-listposition=lonely] {
                    border: 0
                }

                .rhHoTC[data-state~=link]:hover .aWTgIN,.rhHoTC[data-state~=over] .aWTgIN {
                    color: rgb(var(--txth,var(--color_14,color_14)));
                    transition: var(--trans,color .4s ease 0s)
                }

                .rhHoTC[data-state~=selected] .aWTgIN {
                    color: rgb(var(--txts,var(--color_14,color_14)));
                    transition: var(--trans,color .4s ease 0s)
                }

                .rhHoTC[data-state~=drop] {
                    border: 0;
                    border-top: 1px solid rgba(var(--sep,var(--color_15,color_15)),var(--alpha-sep,1));
                    display: block;
                    width: 100%
                }

                .rhHoTC[data-state~=drop] .aWTgIN {
                    display: inline-block;
                    padding: 0 .5em
                }

                .rhHoTC[data-state~=drop] .Zw7XIs {
                    padding: 0
                }

                .rhHoTC[data-listposition=dropLonely],.rhHoTC[data-listposition=top] {
                    border: 0
                }

                .GUSTu5 {
                    overflow-x: hidden
                }

                .GUSTu5 .ONlyPu {
                    display: flex;
                    flex-direction: column;
                    height: 100%;
                    width: 100%
                }

                .GUSTu5 .ONlyPu .BStpMp {
                    flex: 1
                }

                .GUSTu5 .ONlyPu .qDaKPQ {
                    height: calc(100% - (var(--menuTotalBordersY, 0px)));
                    overflow: visible;
                    white-space: nowrap;
                    width: calc(100% - (var(--menuTotalBordersX, 0px)))
                }

                .GUSTu5 .ONlyPu .qDaKPQ .JAo9_G {
                    display: inline-block
                }

                .GUSTu5 .ONlyPu .qDaKPQ .iFrTrN {
                    display: block;
                    width: 100%
                }

                .GUSTu5 .A4aeYo {
                    display: block;
                    opacity: 1;
                    z-index: 99999
                }

                .GUSTu5 .A4aeYo .ByVsPT {
                    display: inherit;
                    overflow: visible;
                    visibility: inherit;
                    white-space: nowrap;
                    width: auto
                }

                .GUSTu5 .A4aeYo.PxlFWD {
                    transition: visibility;
                    transition-delay: .2s;
                    visibility: visible
                }

                .GUSTu5 .A4aeYo .XFe7yJ {
                    display: inline-block
                }

                .GUSTu5 .Iw9hvp {
                    display: none
                }

                .nYRjqR>nav {
                    bottom: 0;
                    left: 0;
                    right: 0;
                    top: 0
                }

                .nYRjqR .A4aeYo,.nYRjqR .qDaKPQ,.nYRjqR>nav {
                    position: absolute
                }

                .nYRjqR .A4aeYo {
                    margin-top: 7px;
                    visibility: hidden
                }

                .nYRjqR [data-dropmode=dropUp] .A4aeYo {
                    margin-bottom: 7px;
                    margin-top: 0
                }

                .nYRjqR .ByVsPT {
                    background-color: rgba(var(--bgDrop,var(--color_11,color_11)),var(--alpha-bgDrop,1));
                    border-radius: var(--rd,0);
                    box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6))
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[StripColumnsContainer_Default].609a8126.min.css">
                :host(:not(.device-mobile-optimized)) .CohWsy,body:not(.device-mobile-optimized) .CohWsy {
                    display: flex
                }

                :host(:not(.device-mobile-optimized)) .V5AUxf,body:not(.device-mobile-optimized) .V5AUxf {
                    -moz-column-gap: var(--margin);
                    column-gap: var(--margin);
                    display: flex;
                    flex-direction: var(--items-direction);
                    margin: 0 auto;
                    position: relative;
                    width: calc(100% - var(--padding)*2)
                }

                :host(:not(.device-mobile-optimized)) .V5AUxf>*,body:not(.device-mobile-optimized) .V5AUxf>* {
                    flex: var(--column-flex) 1 0%;
                    left: 0;
                    margin-bottom: var(--padding);
                    margin-top: var(--padding);
                    min-width: 0;
                    position: relative;
                    top: 0
                }

                :host(.device-mobile-optimized) .V5AUxf,body.device-mobile-optimized .V5AUxf {
                    display: block;
                    padding: var(--padding) 0;
                    position: relative
                }

                :host(.device-mobile-optimized) .V5AUxf>*,body.device-mobile-optimized .V5AUxf>* {
                    margin-bottom: var(--margin);
                    position: relative
                }

                :host(.device-mobile-optimized) .V5AUxf>:first-child,body.device-mobile-optimized .V5AUxf>:first-child {
                    margin-top: var(--firstChildMarginTop,0)
                }

                :host(.device-mobile-optimized) .V5AUxf>:last-child,body.device-mobile-optimized .V5AUxf>:last-child {
                    margin-bottom: var(--lastChildMarginBottom)
                }

                .LIhNy3 {
                    backface-visibility: hidden
                }

                .HlRz5e {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .HlRz5e img {
                    max-width: var(--wix-img-max-width,100%)
                }

                .HlRz5e[data-animate-blur] img {
                    filter: blur(9px);
                    transition: filter .8s ease-in
                }

                .HlRz5e[data-animate-blur] img[data-load-done] {
                    filter: none
                }

                ._1hLNj {
                    display: block
                }

                ._1hLNj,.if7Vw2 {
                    height: 100%;
                    width: 100%
                }

                .if7Vw2 {
                    left: 0;
                    -webkit-mask-image: var(--mask-image,none);
                    mask-image: var(--mask-image,none);
                    -webkit-mask-position: var(--mask-position,0);
                    mask-position: var(--mask-position,0);
                    -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                    mask-repeat: var(--mask-repeat,no-repeat);
                    -webkit-mask-size: var(--mask-size,100%);
                    mask-size: var(--mask-size,100%);
                    overflow: hidden;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: absolute;
                    top: 0
                }

                .if7Vw2.f0uTJH {
                    clip: rect(0,auto,auto,0)
                }

                .if7Vw2 .i1tH8h {
                    height: 100%;
                    position: absolute;
                    top: 0;
                    width: 100%
                }

                .if7Vw2 .DXi4PB {
                    height: var(--fill-layer-image-height,100%);
                    opacity: var(--fill-layer-image-opacity)
                }

                .if7Vw2 .DXi4PB img {
                    height: 100%;
                    width: 100%
                }

                @supports(-webkit-hyphens: none) {
                    .if7Vw2.f0uTJH {
                        clip:auto;
                        -webkit-clip-path: inset(0)
                    }
                }

                .wG8dni {
                    height: 100%
                }

                .tcElKx {
                    background-color: var(--bg-overlay-color);
                    background-image: var(--bg-gradient);
                    transition: var(--inherit-transition)
                }

                .ImALHf,.Ybjs9b {
                    opacity: var(--fill-layer-video-opacity)
                }

                .UWmm3w {
                    bottom: var(--media-padding-bottom);
                    height: var(--media-padding-height);
                    position: absolute;
                    top: var(--media-padding-top);
                    width: 100%
                }

                .Yjj1af {
                    transform: scale(var(--scale,1));
                    transition: var(--transform-duration,transform 0s)
                }

                .ImALHf {
                    height: 100%;
                    position: relative;
                    width: 100%
                }

                wix-media-canvas {
                    display: block;
                    height: 100%
                }

                .KCM6zk {
                    opacity: var(--fill-layer-video-opacity,var(--fill-layer-image-opacity,1))
                }

                .KCM6zk .DXi4PB,.KCM6zk .ImALHf,.KCM6zk .Ybjs9b {
                    opacity: 1
                }

                ._uqPqy {
                    clip-path: var(--fill-layer-clip)
                }

                ._uqPqy,.eKyYhK {
                    position: absolute;
                    top: 0
                }

                ._uqPqy,.eKyYhK,.x0mqQS img {
                    height: 100%;
                    width: 100%
                }

                .pnCr6P {
                    opacity: 0
                }

                .blf7sp,.pnCr6P {
                    position: absolute;
                    top: 0
                }

                .blf7sp {
                    height: 0;
                    left: 0;
                    overflow: hidden;
                    width: 0
                }

                .rWP3Gv {
                    left: 0;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: var(--fill-layer-background-media-position)
                }

                .Tr4n3d,.rWP3Gv,.wRqk6s {
                    height: 100%;
                    top: 0;
                    width: 100%
                }

                .wRqk6s {
                    position: absolute
                }

                .Tr4n3d {
                    background-color: var(--fill-layer-background-overlay-color);
                    opacity: var(--fill-layer-background-overlay-blend-opacity-fallback,1);
                    position: var(--fill-layer-background-overlay-position);
                    transform: var(--fill-layer-background-overlay-transform)
                }

                @supports(mix-blend-mode: overlay) {
                    .Tr4n3d {
                        mix-blend-mode:var(--fill-layer-background-overlay-blend-mode);
                        opacity: var(--fill-layer-background-overlay-blend-opacity,1)
                    }
                }

                .VXAmO2 {
                    --divider-pin-height__: min(1,calc(var(--divider-layers-pin-factor__) + 1));
                    --divider-pin-layer-height__: var(--divider-layers-pin-factor__);
                    --divider-pin-border__: min(1,calc(var(--divider-layers-pin-factor__) / -1 + 1));
                    height: calc(var(--divider-height__) + var(--divider-pin-height__)*var(--divider-layers-size__)*var(--divider-layers-y__))
                }

                .VXAmO2,.VXAmO2 .dy3w_9 {
                    left: 0;
                    position: absolute;
                    width: 100%
                }

                .VXAmO2 .dy3w_9 {
                    --divider-layer-i__: var(--divider-layer-i,0);
                    background-position: left calc(50% + var(--divider-offset-x__) + var(--divider-layers-x__)*var(--divider-layer-i__)) bottom;
                    background-repeat: repeat-x;
                    border-bottom-style: solid;
                    border-bottom-width: calc(var(--divider-pin-border__)*var(--divider-layer-i__)*var(--divider-layers-y__));
                    height: calc(var(--divider-height__) + var(--divider-pin-layer-height__)*var(--divider-layer-i__)*var(--divider-layers-y__));
                    opacity: calc(1 - var(--divider-layer-i__)/(var(--divider-layer-i__) + 1))
                }

                .UORcXs {
                    --divider-height__: var(--divider-top-height,auto);
                    --divider-offset-x__: var(--divider-top-offset-x,0px);
                    --divider-layers-size__: var(--divider-top-layers-size,0);
                    --divider-layers-y__: var(--divider-top-layers-y,0px);
                    --divider-layers-x__: var(--divider-top-layers-x,0px);
                    --divider-layers-pin-factor__: var(--divider-top-layers-pin-factor,0);
                    border-top: var(--divider-top-padding,0) solid var(--divider-top-color,currentColor);
                    opacity: var(--divider-top-opacity,1);
                    top: 0;
                    transform: var(--divider-top-flip,scaleY(-1))
                }

                .UORcXs .dy3w_9 {
                    background-image: var(--divider-top-image,none);
                    background-size: var(--divider-top-size,contain);
                    border-color: var(--divider-top-color,currentColor);
                    bottom: 0;
                    filter: var(--divider-top-filter,none)
                }

                .UORcXs .dy3w_9[data-divider-layer="1"] {
                    display: var(--divider-top-layer-1-display,block)
                }

                .UORcXs .dy3w_9[data-divider-layer="2"] {
                    display: var(--divider-top-layer-2-display,block)
                }

                .UORcXs .dy3w_9[data-divider-layer="3"] {
                    display: var(--divider-top-layer-3-display,block)
                }

                .Io4VUz {
                    --divider-height__: var(--divider-bottom-height,auto);
                    --divider-offset-x__: var(--divider-bottom-offset-x,0px);
                    --divider-layers-size__: var(--divider-bottom-layers-size,0);
                    --divider-layers-y__: var(--divider-bottom-layers-y,0px);
                    --divider-layers-x__: var(--divider-bottom-layers-x,0px);
                    --divider-layers-pin-factor__: var(--divider-bottom-layers-pin-factor,0);
                    border-bottom: var(--divider-bottom-padding,0) solid var(--divider-bottom-color,currentColor);
                    bottom: 0;
                    opacity: var(--divider-bottom-opacity,1);
                    transform: var(--divider-bottom-flip,none)
                }

                .Io4VUz .dy3w_9 {
                    background-image: var(--divider-bottom-image,none);
                    background-size: var(--divider-bottom-size,contain);
                    border-color: var(--divider-bottom-color,currentColor);
                    bottom: 0;
                    filter: var(--divider-bottom-filter,none)
                }

                .Io4VUz .dy3w_9[data-divider-layer="1"] {
                    display: var(--divider-bottom-layer-1-display,block)
                }

                .Io4VUz .dy3w_9[data-divider-layer="2"] {
                    display: var(--divider-bottom-layer-2-display,block)
                }

                .Io4VUz .dy3w_9[data-divider-layer="3"] {
                    display: var(--divider-bottom-layer-3-display,block)
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[Column_DefaultColumn].3eb2cecd.min.css">
                .YzqVVZ {
                    overflow: visible;
                    position: relative
                }

                .mwF7X1 {
                    backface-visibility: hidden
                }

                .YGilLk {
                    cursor: pointer
                }

                .HlRz5e {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .HlRz5e img {
                    max-width: var(--wix-img-max-width,100%)
                }

                .HlRz5e[data-animate-blur] img {
                    filter: blur(9px);
                    transition: filter .8s ease-in
                }

                .HlRz5e[data-animate-blur] img[data-load-done] {
                    filter: none
                }

                .I5zqsT {
                    display: block
                }

                .I5zqsT,.MW5IWV {
                    height: 100%;
                    width: 100%
                }

                .MW5IWV {
                    left: 0;
                    -webkit-mask-image: var(--mask-image,none);
                    mask-image: var(--mask-image,none);
                    -webkit-mask-position: var(--mask-position,0);
                    mask-position: var(--mask-position,0);
                    -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                    mask-repeat: var(--mask-repeat,no-repeat);
                    -webkit-mask-size: var(--mask-size,100%);
                    mask-size: var(--mask-size,100%);
                    overflow: hidden;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: absolute;
                    top: 0
                }

                .MW5IWV.N3eg0s {
                    clip: rect(0,auto,auto,0)
                }

                .MW5IWV .Kv1aVt {
                    height: 100%;
                    position: absolute;
                    top: 0;
                    width: 100%
                }

                .MW5IWV .dLPlxY {
                    height: var(--fill-layer-image-height,100%);
                    opacity: var(--fill-layer-image-opacity)
                }

                .MW5IWV .dLPlxY img {
                    height: 100%;
                    width: 100%
                }

                @supports(-webkit-hyphens: none) {
                    .MW5IWV.N3eg0s {
                        clip:auto;
                        -webkit-clip-path: inset(0)
                    }
                }

                .VgO9Yg {
                    height: 100%
                }

                .LWbAav {
                    background-color: var(--bg-overlay-color);
                    background-image: var(--bg-gradient);
                    transition: var(--inherit-transition)
                }

                .K_YxMd,.yK6aSC {
                    opacity: var(--fill-layer-video-opacity)
                }

                .NGjcJN {
                    bottom: var(--media-padding-bottom);
                    height: var(--media-padding-height);
                    position: absolute;
                    top: var(--media-padding-top);
                    width: 100%
                }

                .mNGsUM {
                    transform: scale(var(--scale,1));
                    transition: var(--transform-duration,transform 0s)
                }

                .K_YxMd {
                    height: 100%;
                    position: relative;
                    width: 100%
                }

                wix-media-canvas {
                    display: block;
                    height: 100%
                }

                .I8xA4L {
                    opacity: var(--fill-layer-video-opacity,var(--fill-layer-image-opacity,1))
                }

                .I8xA4L .K_YxMd,.I8xA4L .dLPlxY,.I8xA4L .yK6aSC {
                    opacity: 1
                }

                .bX9O_S {
                    clip-path: var(--fill-layer-clip)
                }

                .Z_wCwr,.bX9O_S {
                    position: absolute;
                    top: 0
                }

                .Jxk_UL img,.Z_wCwr,.bX9O_S {
                    height: 100%;
                    width: 100%
                }

                .K8MSra {
                    opacity: 0
                }

                .K8MSra,.YTb3b4 {
                    position: absolute;
                    top: 0
                }

                .YTb3b4 {
                    height: 0;
                    left: 0;
                    overflow: hidden;
                    width: 0
                }

                .SUz0WK {
                    left: 0;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: var(--fill-layer-background-media-position)
                }

                .FNxOn5,.SUz0WK,.m4khSP {
                    height: 100%;
                    top: 0;
                    width: 100%
                }

                .FNxOn5 {
                    position: absolute
                }

                .m4khSP {
                    background-color: var(--fill-layer-background-overlay-color);
                    opacity: var(--fill-layer-background-overlay-blend-opacity-fallback,1);
                    position: var(--fill-layer-background-overlay-position);
                    transform: var(--fill-layer-background-overlay-transform)
                }

                @supports(mix-blend-mode: overlay) {
                    .m4khSP {
                        mix-blend-mode:var(--fill-layer-background-overlay-blend-mode);
                        opacity: var(--fill-layer-background-overlay-blend-opacity,1)
                    }
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[FreemiumBannerDesktop].878df411.min.css">
                .ytGGBw {
                    width: 100%
                }

                .ytGGBw.U3zsen {
                    --display: none;
                    display: var(--display)
                }

                .ytGGBw.wDEwXV {
                    display: block;
                    visibility: visible
                }

                .ytGGBw .RMGHU6 {
                    direction: rtl
                }

                .ytGGBw .ZdV7_s {
                    direction: ltr
                }

                .ytGGBw.czJOIz {
                    position: fixed;
                    top: 0;
                    z-index: var(--above-all-z-index)
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW01-35Thin;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/56be84de-9d60-4089-8df0-0ea6ec786b84.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/56be84de-9d60-4089-8df0-0ea6ec786b84.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/50d35bbc-dfd4-48f1-af16-cf058f69421d.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/278bef59-6be1-4800-b5ac-1f769ab47430.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/2e309b1b-08b8-477f-bc9e-7067cf0af0b3.svg#2e309b1b-08b8-477f-bc9e-7067cf0af0b3) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW01-45Ligh;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/ae1656aa-5f8f-4905-aed0-93e667bd6e4a.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/ae1656aa-5f8f-4905-aed0-93e667bd6e4a.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/530dee22-e3c1-4e9f-bf62-c31d510d9656.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/688ab72b-4deb-4e15-a088-89166978d469.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/7816f72f-f47e-4715-8cd7-960e3723846a.svg#7816f72f-f47e-4715-8cd7-960e3723846a) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW01-55Roma;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b7693a83-b861-4aa6-85e0-9ecf676bc4d6.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b7693a83-b861-4aa6-85e0-9ecf676bc4d6.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/bcf54343-d033-41ee-bbd7-2b77df3fe7ba.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b0ffdcf0-26da-47fd-8485-20e4a40d4b7d.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/da09f1f1-062a-45af-86e1-2bbdb3dd94f9.svg#da09f1f1-062a-45af-86e1-2bbdb3dd94f9) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW01-65Medi;
                    font-weight: 700;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/07fe0fec-b63f-4963-8ee1-535528b67fdb.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/07fe0fec-b63f-4963-8ee1-535528b67fdb.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/60be5c39-863e-40cb-9434-6ebafb62ab2b.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/4c6503c9-859b-4d3b-a1d5-2d42e1222415.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/36c182c6-ef98-4021-9b0d-d63122c2bbf5.svg#36c182c6-ef98-4021-9b0d-d63122c2bbf5) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW02-35Thin;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/30b6ffc3-3b64-40dd-9ff8-a3a850daf535.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/30b6ffc3-3b64-40dd-9ff8-a3a850daf535.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/775a65da-14aa-4634-be95-6724c05fd522.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/988eaaa7-5565-4f65-bb17-146b650ce9e9.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/3503a1a6-91c3-4c42-8e66-2ea7b2b57541.svg#3503a1a6-91c3-4c42-8e66-2ea7b2b57541) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW02-45Ligh;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/88fcd49a-13c7-4d0c-86b1-ad1e258bd75d.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/88fcd49a-13c7-4d0c-86b1-ad1e258bd75d.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/9a2e4855-380f-477f-950e-d98e8db54eac.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/fa82d0ee-4fbd-4cc9-bf9f-226ad1fcbae2.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/48d599a6-92b5-4d43-a4ac-8959f6971853.svg#48d599a6-92b5-4d43-a4ac-8959f6971853) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW02-55Roma;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/0b3a3fca-0fad-402b-bd38-fdcbad1ef776.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/0b3a3fca-0fad-402b-bd38-fdcbad1ef776.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/d5af76d8-a90b-4527-b3a3-182207cc3250.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/1d238354-d156-4dde-89ea-4770ef04b9f9.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b68875cb-14a9-472e-8177-0247605124d7.svg#b68875cb-14a9-472e-8177-0247605124d7) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW02-65Medi;
                    font-weight: 700;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/55f60419-09c3-42bd-b81f-1983ff093852.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/55f60419-09c3-42bd-b81f-1983ff093852.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b4a262e-3342-44e2-8ad7-719998a68134.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/4a3ef5d8-cfd9-4b96-bd67-90215512f1e5.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/58ab5075-53ea-46e6-9783-cbb335665f88.svg#58ab5075-53ea-46e6-9783-cbb335665f88) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW10-35Thin;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/93b6bf6a-418e-4a8f-8f79-cb9c99ef3e32.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/93b6bf6a-418e-4a8f-8f79-cb9c99ef3e32.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/c881c21b-4148-4a11-a65d-f35e42999bc8.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/03634cf1-a9c9-4e13-b049-c90d830423d4.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/1bc99c0a-298b-46f9-b325-18b5e5169795.svg#1bc99c0a-298b-46f9-b325-18b5e5169795) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW10-45Ligh;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b85c7cc-6ad4-4226-83f5-9d19e2974123.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b85c7cc-6ad4-4226-83f5-9d19e2974123.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/835e7b4f-b524-4374-b57b-9a8fc555fd4e.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/2c694ef6-9615-473e-8cf4-d8d00c6bd973.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/3fc84193-a13f-4fe8-87f7-238748a4ac54.svg#3fc84193-a13f-4fe8-87f7-238748a4ac54) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW10-65Medi;
                    font-weight: 700;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/7092fdcc-7036-48ce-ae23-cfbc9be2e3b0.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/7092fdcc-7036-48ce-ae23-cfbc9be2e3b0.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/5b29e833-1b7a-40ab-82a5-cfd69c8650f4.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/b0298148-2d59-44d1-9ec9-1ca6bb097603.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/ae1dea8c-a953-4845-b616-74a257ba72e6.svg#ae1dea8c-a953-4845-b616-74a257ba72e6) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: wixFreemiumFontW10-55Roma;
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/f1feaed7-6bce-400a-a07e-a893ae43a680.eot?#iefix);
                    src: url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/f1feaed7-6bce-400a-a07e-a893ae43a680.eot?#iefix) format("eot"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/8ac9e38d-29c6-41ea-8e47-4ae4d2b1a4e1.woff) format("woff"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/4bd09087-655e-4abb-844c-dccdeb68003d.ttf) format("truetype"),url(//static.parastorage.com/services/third-party/fonts/Helvetica/Fonts/df234d87-eada-4058-aa80-5871e7fbe1c3.svg#df234d87-eada-4058-aa80-5871e7fbe1c3) format("svg")
                }

                @font-face {
                    font-display: swap;
                    font-family: Madefor-Text;
                    font-weight: 400;
                    src: url(//static.parastorage.com/services/santa-resources/resources/viewer/user-site-fonts/fonts/WixMadefor/v3/WixMadeforTextVF_W_Wght.woff2) format("woff2-variations"),url(//static.parastorage.com/services/santa-resources/resources/viewer/user-site-fonts/fonts/WixMadefor/v3/WixMadeforText_W_Rg.woff2) format("woff2"),url(//static.parastorage.com/services/santa-resources/resources/viewer/user-site-fonts/fonts/WixMadefor/v3/WixMadeforText_W_Rg.woff) format("woff")
                }

                .N6oJ0x {
                    width: 100%
                }

                .N6oJ0x.YXHWcl {
                    --display: none;
                    display: var(--display)
                }

                .N6oJ0x.crE6R7 {
                    display: block;
                    visibility: visible
                }

                .N6oJ0x .I9E5U_ {
                    direction: rtl
                }

                .N6oJ0x .Oxzvyr {
                    direction: ltr
                }

                .N6oJ0x.L27qsU {
                    position: fixed;
                    top: 0;
                    z-index: var(--above-all-z-index)
                }

                .EFLBov .YD5pSO {
                    align-items: center;
                    background: #eff1f2;
                    border-bottom: 3px solid #a0138e;
                    box-sizing: border-box;
                    display: flex;
                    height: 50px;
                    justify-content: center;
                    width: 100%
                }

                .EFLBov .YD5pSO.mlxr6g {
                    background-color: red;
                    border: none
                }

                .EFLBov .YD5pSO:focus {
                    box-shadow: 0 0 0 1px #fff,0 0 0 3px #116dff,inset -2px 2px 0 0 #116dff,inset 2px 2px 0 0 #116dff,inset 0 3px 0 0 #fff!important
                }

                .EFLBov .YD5pSO>.aGHwBE {
                    align-items: center;
                    display: flex
                }

                .EFLBov .YD5pSO>.aGHwBE .areOb6 {
                    color: #20303c;
                    flex-shrink: 0;
                    font-family: wixFreemiumFontW01-65Medi,wixFreemiumFontW02-65Medi,wixFreemiumFontW10-65Medi,Helvetica Neue,Helvetica,Arial,メイリオ,meiryo,ヒラギノ角ゴ pro w3,hiragino kaku gothic pro,sans-serif;
                    font-size: 14px;
                    line-height: 24px
                }

                .EFLBov .YD5pSO>.aGHwBE .areOb6 .dTTUA9 {
                    direction: ltr;
                    display: inline-flex
                }

                .EFLBov .YD5pSO>.aGHwBE .areOb6 .dTTUA9 ._4i7Zy {
                    fill: #20303c;
                    height: 16px;
                    padding-bottom: 6px;
                    vertical-align: middle;
                    width: 36px
                }

                .EFLBov .YD5pSO>.aGHwBE .areOb6 .dTTUA9 ._4i7Zy .o4sLYL {
                    fill: #fc0
                }

                .EFLBov .YD5pSO>.aGHwBE .areOb6 .dTTUA9 .uJDaUS {
                    color: #20303c
                }

                .EFLBov .YD5pSO>.aGHwBE .O0tKs2 {
                    align-items: center;
                    border: 1px solid #a0138e;
                    border-radius: 17px;
                    color: #a0138e;
                    display: inline-flex;
                    flex-shrink: 0;
                    font-family: wixFreemiumFontW01-65Medi,wixFreemiumFontW02-65Medi,wixFreemiumFontW10-65Medi,Helvetica Neue,Helvetica,Arial,メイリオ,meiryo,ヒラギノ角ゴ pro w3,hiragino kaku gothic pro,sans-serif;
                    font-size: 14px;
                    height: 35px;
                    justify-content: center;
                    text-align: center;
                    width: 112px
                }

                .EFLBov .YD5pSO>.aGHwBE .O0tKs2.Oxzvyr {
                    margin-left: 6px
                }

                .EFLBov .YD5pSO>.aGHwBE .O0tKs2.I9E5U_ {
                    margin-right: 6px
                }

                .EFLBov .YD5pSO:not(.mlxr6g):hover {
                    background: #fff;
                    cursor: pointer
                }

                .EFLBov .YD5pSO:not(.mlxr6g):hover .O0tKs2 {
                    background-color: #a0138e;
                    color: #fff
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[SkipToContentButton].39deac6a.min.css">
                .LHrbPP {
                    background: #fff;
                    border-radius: 24px;
                    color: #116dff;
                    cursor: pointer;
                    font-family: Helvetica,Arial,メイリオ,meiryo,ヒラギノ角ゴ pro w3,hiragino kaku gothic pro,sans-serif;
                    font-size: 14px;
                    height: 0;
                    left: 50%;
                    margin-left: -94px;
                    opacity: 0;
                    padding: 0 24px 0 24px;
                    pointer-events: none;
                    position: absolute;
                    top: 60px;
                    width: 0;
                    z-index: 9999
                }

                .LHrbPP:focus {
                    border: 2px solid;
                    height: 40px;
                    opacity: 1;
                    pointer-events: auto;
                    width: auto
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt_bootstrap-classic.c1b043a8.min.css">
                .PlZyDq {
                    touch-action: manipulation
                }

                .uDW_Qe {
                    align-items: center;
                    box-sizing: border-box;
                    display: flex;
                    justify-content: var(--label-align);
                    min-width: 100%;
                    text-align: initial;
                    width: -moz-max-content;
                    width: max-content
                }

                .uDW_Qe:before {
                    max-width: var(--margin-start,0)
                }

                .uDW_Qe:after,.uDW_Qe:before {
                    align-self: stretch;
                    content: "";
                    flex-grow: 1
                }

                .uDW_Qe:after {
                    max-width: var(--margin-end,0)
                }

                .FubTgk {
                    height: 100%
                }

                .FubTgk .uDW_Qe {
                    border-radius: var(--corvid-border-radius,var(--rd,0));
                    bottom: 0;
                    box-shadow: var(--shd,0 1px 4px rgba(0,0,0,.6));
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0;
                    transition: var(--trans1,border-color .4s ease 0s,background-color .4s ease 0s)
                }

                .FubTgk .uDW_Qe:link,.FubTgk .uDW_Qe:visited {
                    border-color: transparent
                }

                .FubTgk .l7_2fn {
                    color: var(--corvid-color,rgb(var(--txt,var(--color_15,color_15))));
                    font: var(--fnt,var(--font_5));
                    margin: 0;
                    position: relative;
                    transition: var(--trans2,color .4s ease 0s);
                    white-space: nowrap
                }

                .FubTgk[aria-disabled=false] .uDW_Qe {
                    background-color: var(--corvid-background-color,rgba(var(--bg,var(--color_17,color_17)),var(--alpha-bg,1)));
                    border: solid var(--corvid-border-color,rgba(var(--brd,var(--color_15,color_15)),var(--alpha-brd,1))) var(--corvid-border-width,var(--brw,0));
                    cursor: pointer!important
                }

                :host(.device-mobile-optimized) .FubTgk[aria-disabled=false]:active .uDW_Qe,body.device-mobile-optimized .FubTgk[aria-disabled=false]:active .uDW_Qe {
                    background-color: var(--corvid-hover-background-color,rgba(var(--bgh,var(--color_18,color_18)),var(--alpha-bgh,1)));
                    border-color: var(--corvid-hover-border-color,rgba(var(--brdh,var(--color_15,color_15)),var(--alpha-brdh,1)))
                }

                :host(.device-mobile-optimized) .FubTgk[aria-disabled=false]:active .l7_2fn,body.device-mobile-optimized .FubTgk[aria-disabled=false]:active .l7_2fn {
                    color: var(--corvid-hover-color,rgb(var(--txth,var(--color_15,color_15))))
                }

                :host(:not(.device-mobile-optimized)) .FubTgk[aria-disabled=false]:hover .uDW_Qe,body:not(.device-mobile-optimized) .FubTgk[aria-disabled=false]:hover .uDW_Qe {
                    background-color: var(--corvid-hover-background-color,rgba(var(--bgh,var(--color_18,color_18)),var(--alpha-bgh,1)));
                    border-color: var(--corvid-hover-border-color,rgba(var(--brdh,var(--color_15,color_15)),var(--alpha-brdh,1)))
                }

                :host(:not(.device-mobile-optimized)) .FubTgk[aria-disabled=false]:hover .l7_2fn,body:not(.device-mobile-optimized) .FubTgk[aria-disabled=false]:hover .l7_2fn {
                    color: var(--corvid-hover-color,rgb(var(--txth,var(--color_15,color_15))))
                }

                .FubTgk[aria-disabled=true] .uDW_Qe {
                    background-color: var(--corvid-disabled-background-color,rgba(var(--bgd,204,204,204),var(--alpha-bgd,1)));
                    border-color: var(--corvid-disabled-border-color,rgba(var(--brdd,204,204,204),var(--alpha-brdd,1)));
                    border-style: solid;
                    border-width: var(--corvid-border-width,var(--brw,0))
                }

                .FubTgk[aria-disabled=true] .l7_2fn {
                    color: var(--corvid-disabled-color,rgb(var(--txtd,255,255,255)))
                }

                .uUxqWY {
                    align-items: center;
                    box-sizing: border-box;
                    display: flex;
                    justify-content: var(--label-align);
                    min-width: 100%;
                    text-align: initial;
                    width: -moz-max-content;
                    width: max-content
                }

                .uUxqWY:before {
                    max-width: var(--margin-start,0)
                }

                .uUxqWY:after,.uUxqWY:before {
                    align-self: stretch;
                    content: "";
                    flex-grow: 1
                }

                .uUxqWY:after {
                    max-width: var(--margin-end,0)
                }

                .Vq4wYb[aria-disabled=false] .uUxqWY {
                    cursor: pointer
                }

                :host(.device-mobile-optimized) .Vq4wYb[aria-disabled=false]:active .wJVzSK,body.device-mobile-optimized .Vq4wYb[aria-disabled=false]:active .wJVzSK {
                    color: var(--corvid-hover-color,rgb(var(--txth,var(--color_15,color_15))));
                    transition: var(--trans,color .4s ease 0s)
                }

                :host(:not(.device-mobile-optimized)) .Vq4wYb[aria-disabled=false]:hover .wJVzSK,body:not(.device-mobile-optimized) .Vq4wYb[aria-disabled=false]:hover .wJVzSK {
                    color: var(--corvid-hover-color,rgb(var(--txth,var(--color_15,color_15))));
                    transition: var(--trans,color .4s ease 0s)
                }

                .Vq4wYb .uUxqWY {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .Vq4wYb .wJVzSK {
                    color: var(--corvid-color,rgb(var(--txt,var(--color_15,color_15))));
                    font: var(--fnt,var(--font_5));
                    transition: var(--trans,color .4s ease 0s);
                    white-space: nowrap
                }

                .Vq4wYb[aria-disabled=true] .wJVzSK {
                    color: var(--corvid-disabled-color,rgb(var(--txtd,255,255,255)))
                }

                :host(:not(.device-mobile-optimized)) .CohWsy,body:not(.device-mobile-optimized) .CohWsy {
                    display: flex
                }

                :host(:not(.device-mobile-optimized)) .V5AUxf,body:not(.device-mobile-optimized) .V5AUxf {
                    -moz-column-gap: var(--margin);
                    column-gap: var(--margin);
                    display: flex;
                    flex-direction: var(--items-direction);
                    margin: 0 auto;
                    position: relative;
                    width: calc(100% - var(--padding)*2)
                }

                :host(:not(.device-mobile-optimized)) .V5AUxf>*,body:not(.device-mobile-optimized) .V5AUxf>* {
                    flex: var(--column-flex) 1 0%;
                    left: 0;
                    margin-bottom: var(--padding);
                    margin-top: var(--padding);
                    min-width: 0;
                    position: relative;
                    top: 0
                }

                :host(.device-mobile-optimized) .V5AUxf,body.device-mobile-optimized .V5AUxf {
                    display: block;
                    padding: var(--padding) 0;
                    position: relative
                }

                :host(.device-mobile-optimized) .V5AUxf>*,body.device-mobile-optimized .V5AUxf>* {
                    margin-bottom: var(--margin);
                    position: relative
                }

                :host(.device-mobile-optimized) .V5AUxf>:first-child,body.device-mobile-optimized .V5AUxf>:first-child {
                    margin-top: var(--firstChildMarginTop,0)
                }

                :host(.device-mobile-optimized) .V5AUxf>:last-child,body.device-mobile-optimized .V5AUxf>:last-child {
                    margin-bottom: var(--lastChildMarginBottom)
                }

                .LIhNy3 {
                    backface-visibility: hidden
                }

                .HlRz5e {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .HlRz5e img {
                    max-width: var(--wix-img-max-width,100%)
                }

                .HlRz5e[data-animate-blur] img {
                    filter: blur(9px);
                    transition: filter .8s ease-in
                }

                .HlRz5e[data-animate-blur] img[data-load-done] {
                    filter: none
                }

                ._1hLNj {
                    display: block
                }

                ._1hLNj,.if7Vw2 {
                    height: 100%;
                    width: 100%
                }

                .if7Vw2 {
                    left: 0;
                    -webkit-mask-image: var(--mask-image,none);
                    mask-image: var(--mask-image,none);
                    -webkit-mask-position: var(--mask-position,0);
                    mask-position: var(--mask-position,0);
                    -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                    mask-repeat: var(--mask-repeat,no-repeat);
                    -webkit-mask-size: var(--mask-size,100%);
                    mask-size: var(--mask-size,100%);
                    overflow: hidden;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: absolute;
                    top: 0
                }

                .if7Vw2.f0uTJH {
                    clip: rect(0,auto,auto,0)
                }

                .if7Vw2 .i1tH8h {
                    height: 100%;
                    position: absolute;
                    top: 0;
                    width: 100%
                }

                .if7Vw2 .DXi4PB {
                    height: var(--fill-layer-image-height,100%);
                    opacity: var(--fill-layer-image-opacity)
                }

                .if7Vw2 .DXi4PB img {
                    height: 100%;
                    width: 100%
                }

                @supports(-webkit-hyphens: none) {
                    .if7Vw2.f0uTJH {
                        clip:auto;
                        -webkit-clip-path: inset(0)
                    }
                }

                .wG8dni {
                    height: 100%
                }

                .tcElKx {
                    background-color: var(--bg-overlay-color);
                    background-image: var(--bg-gradient);
                    transition: var(--inherit-transition)
                }

                .ImALHf,.Ybjs9b {
                    opacity: var(--fill-layer-video-opacity)
                }

                .UWmm3w {
                    bottom: var(--media-padding-bottom);
                    height: var(--media-padding-height);
                    position: absolute;
                    top: var(--media-padding-top);
                    width: 100%
                }

                .Yjj1af {
                    transform: scale(var(--scale,1));
                    transition: var(--transform-duration,transform 0s)
                }

                .ImALHf {
                    height: 100%;
                    position: relative;
                    width: 100%
                }

                .KCM6zk {
                    opacity: var(--fill-layer-video-opacity,var(--fill-layer-image-opacity,1))
                }

                .KCM6zk .DXi4PB,.KCM6zk .ImALHf,.KCM6zk .Ybjs9b {
                    opacity: 1
                }

                ._uqPqy {
                    clip-path: var(--fill-layer-clip)
                }

                ._uqPqy,.eKyYhK {
                    position: absolute;
                    top: 0
                }

                ._uqPqy,.eKyYhK,.x0mqQS img {
                    height: 100%;
                    width: 100%
                }

                .pnCr6P {
                    opacity: 0
                }

                .blf7sp,.pnCr6P {
                    position: absolute;
                    top: 0
                }

                .blf7sp {
                    height: 0;
                    left: 0;
                    overflow: hidden;
                    width: 0
                }

                .rWP3Gv {
                    left: 0;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: var(--fill-layer-background-media-position)
                }

                .Tr4n3d,.rWP3Gv,.wRqk6s {
                    height: 100%;
                    top: 0;
                    width: 100%
                }

                .wRqk6s {
                    position: absolute
                }

                .Tr4n3d {
                    background-color: var(--fill-layer-background-overlay-color);
                    opacity: var(--fill-layer-background-overlay-blend-opacity-fallback,1);
                    position: var(--fill-layer-background-overlay-position);
                    transform: var(--fill-layer-background-overlay-transform)
                }

                @supports(mix-blend-mode: overlay) {
                    .Tr4n3d {
                        mix-blend-mode:var(--fill-layer-background-overlay-blend-mode);
                        opacity: var(--fill-layer-background-overlay-blend-opacity,1)
                    }
                }

                .VXAmO2 {
                    --divider-pin-height__: min(1,calc(var(--divider-layers-pin-factor__) + 1));
                    --divider-pin-layer-height__: var(--divider-layers-pin-factor__);
                    --divider-pin-border__: min(1,calc(var(--divider-layers-pin-factor__) / -1 + 1));
                    height: calc(var(--divider-height__) + var(--divider-pin-height__)*var(--divider-layers-size__)*var(--divider-layers-y__))
                }

                .VXAmO2,.VXAmO2 .dy3w_9 {
                    left: 0;
                    position: absolute;
                    width: 100%
                }

                .VXAmO2 .dy3w_9 {
                    --divider-layer-i__: var(--divider-layer-i,0);
                    background-position: left calc(50% + var(--divider-offset-x__) + var(--divider-layers-x__)*var(--divider-layer-i__)) bottom;
                    background-repeat: repeat-x;
                    border-bottom-style: solid;
                    border-bottom-width: calc(var(--divider-pin-border__)*var(--divider-layer-i__)*var(--divider-layers-y__));
                    height: calc(var(--divider-height__) + var(--divider-pin-layer-height__)*var(--divider-layer-i__)*var(--divider-layers-y__));
                    opacity: calc(1 - var(--divider-layer-i__)/(var(--divider-layer-i__) + 1))
                }

                .UORcXs {
                    --divider-height__: var(--divider-top-height,auto);
                    --divider-offset-x__: var(--divider-top-offset-x,0px);
                    --divider-layers-size__: var(--divider-top-layers-size,0);
                    --divider-layers-y__: var(--divider-top-layers-y,0px);
                    --divider-layers-x__: var(--divider-top-layers-x,0px);
                    --divider-layers-pin-factor__: var(--divider-top-layers-pin-factor,0);
                    border-top: var(--divider-top-padding,0) solid var(--divider-top-color,currentColor);
                    opacity: var(--divider-top-opacity,1);
                    top: 0;
                    transform: var(--divider-top-flip,scaleY(-1))
                }

                .UORcXs .dy3w_9 {
                    background-image: var(--divider-top-image,none);
                    background-size: var(--divider-top-size,contain);
                    border-color: var(--divider-top-color,currentColor);
                    bottom: 0;
                    filter: var(--divider-top-filter,none)
                }

                .UORcXs .dy3w_9[data-divider-layer="1"] {
                    display: var(--divider-top-layer-1-display,block)
                }

                .UORcXs .dy3w_9[data-divider-layer="2"] {
                    display: var(--divider-top-layer-2-display,block)
                }

                .UORcXs .dy3w_9[data-divider-layer="3"] {
                    display: var(--divider-top-layer-3-display,block)
                }

                .Io4VUz {
                    --divider-height__: var(--divider-bottom-height,auto);
                    --divider-offset-x__: var(--divider-bottom-offset-x,0px);
                    --divider-layers-size__: var(--divider-bottom-layers-size,0);
                    --divider-layers-y__: var(--divider-bottom-layers-y,0px);
                    --divider-layers-x__: var(--divider-bottom-layers-x,0px);
                    --divider-layers-pin-factor__: var(--divider-bottom-layers-pin-factor,0);
                    border-bottom: var(--divider-bottom-padding,0) solid var(--divider-bottom-color,currentColor);
                    bottom: 0;
                    opacity: var(--divider-bottom-opacity,1);
                    transform: var(--divider-bottom-flip,none)
                }

                .Io4VUz .dy3w_9 {
                    background-image: var(--divider-bottom-image,none);
                    background-size: var(--divider-bottom-size,contain);
                    border-color: var(--divider-bottom-color,currentColor);
                    bottom: 0;
                    filter: var(--divider-bottom-filter,none)
                }

                .Io4VUz .dy3w_9[data-divider-layer="1"] {
                    display: var(--divider-bottom-layer-1-display,block)
                }

                .Io4VUz .dy3w_9[data-divider-layer="2"] {
                    display: var(--divider-bottom-layer-2-display,block)
                }

                .Io4VUz .dy3w_9[data-divider-layer="3"] {
                    display: var(--divider-bottom-layer-3-display,block)
                }

                .YzqVVZ {
                    overflow: visible;
                    position: relative
                }

                .mwF7X1 {
                    backface-visibility: hidden
                }

                .YGilLk {
                    cursor: pointer
                }

                .I5zqsT {
                    display: block
                }

                .I5zqsT,.MW5IWV {
                    height: 100%;
                    width: 100%
                }

                .MW5IWV {
                    left: 0;
                    -webkit-mask-image: var(--mask-image,none);
                    mask-image: var(--mask-image,none);
                    -webkit-mask-position: var(--mask-position,0);
                    mask-position: var(--mask-position,0);
                    -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                    mask-repeat: var(--mask-repeat,no-repeat);
                    -webkit-mask-size: var(--mask-size,100%);
                    mask-size: var(--mask-size,100%);
                    overflow: hidden;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: absolute;
                    top: 0
                }

                .MW5IWV.N3eg0s {
                    clip: rect(0,auto,auto,0)
                }

                .MW5IWV .Kv1aVt {
                    height: 100%;
                    position: absolute;
                    top: 0;
                    width: 100%
                }

                .MW5IWV .dLPlxY {
                    height: var(--fill-layer-image-height,100%);
                    opacity: var(--fill-layer-image-opacity)
                }

                .MW5IWV .dLPlxY img {
                    height: 100%;
                    width: 100%
                }

                @supports(-webkit-hyphens: none) {
                    .MW5IWV.N3eg0s {
                        clip:auto;
                        -webkit-clip-path: inset(0)
                    }
                }

                .VgO9Yg {
                    height: 100%
                }

                .LWbAav {
                    background-color: var(--bg-overlay-color);
                    background-image: var(--bg-gradient);
                    transition: var(--inherit-transition)
                }

                .K_YxMd,.yK6aSC {
                    opacity: var(--fill-layer-video-opacity)
                }

                .NGjcJN {
                    bottom: var(--media-padding-bottom);
                    height: var(--media-padding-height);
                    position: absolute;
                    top: var(--media-padding-top);
                    width: 100%
                }

                .mNGsUM {
                    transform: scale(var(--scale,1));
                    transition: var(--transform-duration,transform 0s)
                }

                .K_YxMd {
                    height: 100%;
                    position: relative;
                    width: 100%
                }

                wix-media-canvas {
                    display: block;
                    height: 100%
                }

                .I8xA4L {
                    opacity: var(--fill-layer-video-opacity,var(--fill-layer-image-opacity,1))
                }

                .I8xA4L .K_YxMd,.I8xA4L .dLPlxY,.I8xA4L .yK6aSC {
                    opacity: 1
                }

                .bX9O_S {
                    clip-path: var(--fill-layer-clip)
                }

                .Z_wCwr,.bX9O_S {
                    position: absolute;
                    top: 0
                }

                .Jxk_UL img,.Z_wCwr,.bX9O_S {
                    height: 100%;
                    width: 100%
                }

                .K8MSra {
                    opacity: 0
                }

                .K8MSra,.YTb3b4 {
                    position: absolute;
                    top: 0
                }

                .YTb3b4 {
                    height: 0;
                    left: 0;
                    overflow: hidden;
                    width: 0
                }

                .SUz0WK {
                    left: 0;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: var(--fill-layer-background-media-position)
                }

                .FNxOn5,.SUz0WK,.m4khSP {
                    height: 100%;
                    top: 0;
                    width: 100%
                }

                .FNxOn5 {
                    position: absolute
                }

                .m4khSP {
                    background-color: var(--fill-layer-background-overlay-color);
                    opacity: var(--fill-layer-background-overlay-blend-opacity-fallback,1);
                    position: var(--fill-layer-background-overlay-position);
                    transform: var(--fill-layer-background-overlay-transform)
                }

                @supports(mix-blend-mode: overlay) {
                    .m4khSP {
                        mix-blend-mode:var(--fill-layer-background-overlay-blend-mode);
                        opacity: var(--fill-layer-background-overlay-blend-opacity,1)
                    }
                }

                ._C0cVf {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0;
                    width: 100%
                }

                .hFwGTD {
                    transform: translateY(-100%);
                    transition: .2s ease-in
                }

                .IQgXoP {
                    transition: .2s
                }

                .Nr3Nid {
                    opacity: 0;
                    transition: .2s ease-in
                }

                .Nr3Nid.l4oO6c {
                    z-index: -1!important
                }

                .iQuoC4 {
                    opacity: 1;
                    transition: .2s
                }

                .CJF7A2 {
                    height: auto
                }

                .CJF7A2,.U4Bvut {
                    position: relative;
                    width: 100%
                }

                :host(:not(.device-mobile-optimized)) .G5K6X8,body:not(.device-mobile-optimized) .G5K6X8 {
                    margin-left: calc((100% - var(--site-width))/2);
                    width: var(--site-width)
                }

                .xU8fqS[data-focuscycled=active] {
                    outline: 1px solid transparent
                }

                .xU8fqS[data-focuscycled=active]:not(:focus-within) {
                    outline: 2px solid transparent;
                    transition: outline .01s ease
                }

                .xU8fqS ._4XcTfy {
                    background-color: var(--screenwidth-corvid-background-color,rgba(var(--bg,var(--color_11,color_11)),var(--alpha-bg,1)));
                    border-bottom: var(--brwb,0) solid var(--screenwidth-corvid-border-color,rgba(var(--brd,var(--color_15,color_15)),var(--alpha-brd,1)));
                    border-top: var(--brwt,0) solid var(--screenwidth-corvid-border-color,rgba(var(--brd,var(--color_15,color_15)),var(--alpha-brd,1)));
                    bottom: 0;
                    box-shadow: var(--shd,0 0 5px rgba(0,0,0,.7));
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .xU8fqS .gUbusX {
                    background-color: rgba(var(--bgctr,var(--color_11,color_11)),var(--alpha-bgctr,1));
                    border-radius: var(--rd,0);
                    bottom: var(--brwb,0);
                    top: var(--brwt,0)
                }

                .xU8fqS .G5K6X8,.xU8fqS .gUbusX {
                    left: 0;
                    position: absolute;
                    right: 0
                }

                .xU8fqS .G5K6X8 {
                    bottom: 0;
                    top: 0
                }

                :host(.device-mobile-optimized) .xU8fqS .G5K6X8,body.device-mobile-optimized .xU8fqS .G5K6X8 {
                    left: 10px;
                    right: 10px
                }

                .SPY_vo {
                    pointer-events: none
                }

                .BmZ5pC {
                    min-height: calc(100vh - var(--wix-ads-height));
                    min-width: var(--site-width);
                    position: var(--bg-position);
                    top: var(--wix-ads-height)
                }

                .BmZ5pC,.nTOEE9 {
                    height: 100%;
                    width: 100%
                }

                .nTOEE9 {
                    overflow: hidden;
                    position: relative
                }

                .nTOEE9.sqUyGm:hover {
                    cursor: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAAH6ji2bAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAA3FpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNS1jMDE0IDc5LjE1MTQ4MSwgMjAxMy8wMy8xMy0xMjowOToxNSAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6ODM3MEUzMUU4OTAyMTFFMzk3Q0FCMkFEODdDNzUzMjQiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6ODM3MEUzMUQ4OTAyMTFFMzk3Q0FCMkFEODdDNzUzMjQiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIChXaW5kb3dzKSI+IDx4bXBNTTpEZXJpdmVkRnJvbSBzdFJlZjppbnN0YW5jZUlEPSJ4bXAuaWlkOjk0ZTkyMTRlLThiNDQtNjc0My04MWZiLTZlYjIzYTA2ZjcwNCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz4bqsJgAAACF0lEQVR42mJgQAd8fHz/gdRvRigfxGEACCA4YvwPBMgCbgABBGOAJP6LiooiZBUUFMCC7969Awk6AQQQA1bAxMTUOnXq1P8/f/78j2zdf5BDQDgoKAgiyMgItv0/1AkozlgJlHwPpDWB+AhAACFL1EJVwvBPIGZHd8P/OXPmgI0F2YdmxXQUhX///sVQqK2tDVL4DFkhF8zK2NjY/4aGhshOOMJAJAB5ZjdAADGQCpiB4Cear3uwKQR74vv372BPLFq0CKZ4GnLcdMGiFtnXmzZtQo0Bdnb2r/b29nBFMIwUjkxghby8vHfFxMQwTMQWp0YggZcvX/5HBpqamhgKQdafAQnq6en9j4+P/4/me150nzsCPfYOKrkWKvYCymcjJozPgqIYIMAYcUjKAnEcELsDbVECOpkNiO8B+buAeCEQ3yUqFllYWNYh+4Obm/u/ubn5f0tLy//QPIqM90ATHVagDHTJH5BCfn7+/xcvXvyPC9y7d+8/KHqghv4FYj0M04BxeAOkQEhI6P+vX79QDECOeBj49+/ffzk5OZih91FyP4gAGiIDooH5hIGVlRUsAXQpGMMAMh+Y1xksLCzg5QxGrAFzwAxY2GzYsIGgC48cOYIclsuwBiIbG9sCmCJFRcX/+/fvxwi/EydOwIoDGH6JLQEiA26ga1egxSY2vAUpkcKKEV5iCwVOIObBU8w8RzLYgYHaAAACg5CxaxSLgwAAAABJRU5ErkJggg==),auto
                }

                .nTOEE9.C_JY0G:hover {
                    cursor: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABQAAAAUCAYAAAH6ji2bAAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAA3FpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw/eHBhY2tldCBiZWdpbj0i77u/IiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8+IDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNS1jMDE0IDc5LjE1MTQ4MSwgMjAxMy8wMy8xMy0xMjowOToxNSAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wTU09Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9tbS8iIHhtbG5zOnN0UmVmPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvc1R5cGUvUmVzb3VyY2VSZWYjIiB4bWxuczp4bXA9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC8iIHhtcE1NOk9yaWdpbmFsRG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiIHhtcE1NOkRvY3VtZW50SUQ9InhtcC5kaWQ6N0I4QkNGQTI4OTAyMTFFMzg0RDlBRkM5NDA5QjczRTEiIHhtcE1NOkluc3RhbmNlSUQ9InhtcC5paWQ6N0I4QkNGQTE4OTAyMTFFMzg0RDlBRkM5NDA5QjczRTEiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIChXaW5kb3dzKSI+IDx4bXBNTTpEZXJpdmVkRnJvbSBzdFJlZjppbnN0YW5jZUlEPSJ4bXAuaWlkOjk0ZTkyMTRlLThiNDQtNjc0My04MWZiLTZlYjIzYTA2ZjcwNCIgc3RSZWY6ZG9jdW1lbnRJRD0ieG1wLmRpZDpmMWUzNTlkMS1hYjZhLTNkNDctYmM0ZC03MWMyZDYyMWNmNDgiLz4gPC9yZGY6RGVzY3JpcHRpb24+IDwvcmRmOlJERj4gPC94OnhtcG1ldGE+IDw/eHBhY2tldCBlbmQ9InIiPz7hiSPZAAACGklEQVR42mJgQAd8fHz/gdRvRigfxGEACCA4YvwPBMgCbgABBGOAJP6LiooiZBUUFMCC7969Awk6AQQQA1bAxMTUOnXq1P8/f/78j2zdf5BDQDgoKAgiyMgItv0/1AkozlgJlHwPpDWB+AhAACFL1EJVwvBPIGZHd8P/OXPm/EcHUA3TURT+/fsXQ6G2tjZI4TNkhVwwK2NjY/8bGhoiO+EIA5EA5JndAAHEQCpgBoKfaL7uwaYQHLrfv38He2LRokUwxdOQ46YLFrXIYNOmTagxwM7O/tXe3h4sCYs3EEYKRyawQl5e3rtiYmL/sQH0ODUCCbx8+RJFkaamJoZCkPVnQIJ6enr/4+Pj/6P5nhfd545Aj72DSq6Fir2A8tmICeOzoCgGCDBGHJKyQBwHxO5AW5SATmYD4ntA/i4gXgjEd4mKRRYWlnXI/uDm5v5vbm7+39LS8j80jyLjPdBEhxUoA13yB6SQn5///8WLF//jAvfu3fsPih6ooX+BWA/DNGAc3gApEBIS+v/r16//hMC/f//+y8nJwQy9j2wWC4gAGiIDooH5hIGVlRUsAXQpVq98/PgRVBAwWFhYMDx69AhczkBj7RdyFpgBC5sNGzYQdOGRI0eQw3IZVpvZ2NgWwBQpKir+379/P4ZBJ06cgBUHMPwSWwJEBtxA165Ai01seAtSIoUVI7zEFgqcQMyDp5h5jmSwAwO1AQBU5q033XYWQwAAAABJRU5ErkJggg==),auto
                }

                .RZQnmg {
                    background-color: rgb(var(--color_11));
                    border-radius: 300px;
                    bottom: 0;
                    cursor: pointer;
                    height: 40px;
                    margin: 16px 16px;
                    opacity: 0;
                    pointer-events: none;
                    position: absolute;
                    right: 0;
                    width: 40px
                }

                .RZQnmg path {
                    fill: rgb(var(--color_12))
                }

                .RZQnmg:focus {
                    cursor: auto;
                    opacity: 1;
                    pointer-events: auto
                }

                .rYiAuL {
                    cursor: pointer
                }

                .gSXewE {
                    height: 0;
                    left: 0;
                    overflow: hidden;
                    top: 0;
                    width: 0
                }

                .OJQ_3L,.gSXewE {
                    position: absolute
                }

                .OJQ_3L {
                    background-color: rgb(var(--color_11));
                    border-radius: 300px;
                    bottom: 0;
                    cursor: pointer;
                    height: 40px;
                    margin: 16px 16px;
                    opacity: 0;
                    pointer-events: none;
                    right: 0;
                    width: 40px
                }

                .OJQ_3L path {
                    fill: rgb(var(--color_12))
                }

                .OJQ_3L:focus {
                    cursor: auto;
                    opacity: 1;
                    pointer-events: auto
                }

                .j7pOnl {
                    box-sizing: border-box;
                    height: 100%;
                    width: 100%
                }

                .BI8PVQ {
                    min-height: var(--image-min-height);
                    min-width: var(--image-min-width)
                }

                .BI8PVQ img,img.BI8PVQ {
                    filter: var(--filter-effect-svg-url);
                    -webkit-mask-image: var(--mask-image,none);
                    mask-image: var(--mask-image,none);
                    -webkit-mask-position: var(--mask-position,0);
                    mask-position: var(--mask-position,0);
                    -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                    mask-repeat: var(--mask-repeat,no-repeat);
                    -webkit-mask-size: var(--mask-size,100% 100%);
                    mask-size: var(--mask-size,100% 100%);
                    -o-object-position: var(--object-position);
                    object-position: var(--object-position)
                }

                .MazNVa {
                    left: var(--left,auto);
                    position: var(--position-fixed,static);
                    top: var(--top,auto);
                    z-index: var(--z-index,auto)
                }

                .MazNVa .BI8PVQ img {
                    box-shadow: 0 0 0 #000;
                    position: static;
                    -webkit-user-select: none;
                    -moz-user-select: none;
                    -ms-user-select: none;
                    user-select: none
                }

                .MazNVa .j7pOnl {
                    display: block;
                    overflow: hidden
                }

                .MazNVa .BI8PVQ {
                    overflow: hidden
                }

                .c7cMWz {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .FVGvCX {
                    height: auto;
                    position: relative;
                    width: 100%
                }

                body:not(.responsive) .zK7MhX {
                    align-self: start;
                    grid-area: 1/1/1/1;
                    height: 100%;
                    justify-self: stretch;
                    left: 0;
                    position: relative
                }

                :host(:not(.device-mobile-optimized)) .c7cMWz,body:not(.device-mobile-optimized) .c7cMWz {
                    margin-left: calc((100% - var(--site-width))/2);
                    width: var(--site-width)
                }

                .fEm0Bo .c7cMWz {
                    background-color: rgba(var(--bg,var(--color_11,color_11)),var(--alpha-bg,1));
                    overflow: hidden
                }

                :host(.device-mobile-optimized) .c7cMWz,body.device-mobile-optimized .c7cMWz {
                    left: 10px;
                    right: 10px
                }

                .PFkO7r {
                    bottom: 0;
                    left: 0;
                    position: absolute;
                    right: 0;
                    top: 0
                }

                .HT5ybB {
                    height: auto;
                    position: relative;
                    width: 100%
                }

                body:not(.responsive) .dBAkHi {
                    align-self: start;
                    grid-area: 1/1/1/1;
                    height: 100%;
                    justify-self: stretch;
                    left: 0;
                    position: relative
                }

                :host(:not(.device-mobile-optimized)) .PFkO7r,body:not(.device-mobile-optimized) .PFkO7r {
                    margin-left: calc((100% - var(--site-width))/2);
                    width: var(--site-width)
                }

                :host(.device-mobile-optimized) .PFkO7r,body.device-mobile-optimized .PFkO7r {
                    left: 10px;
                    right: 10px
                }
            </style>
            <style data-href="https://static.parastorage.com/services/editor-elements-library/dist/thunderbolt/rb_wixui.thunderbolt[ClassicSection].6a193895.min.css">
                .MW5IWV {
                    height: 100%;
                    left: 0;
                    -webkit-mask-image: var(--mask-image,none);
                    mask-image: var(--mask-image,none);
                    -webkit-mask-position: var(--mask-position,0);
                    mask-position: var(--mask-position,0);
                    -webkit-mask-repeat: var(--mask-repeat,no-repeat);
                    mask-repeat: var(--mask-repeat,no-repeat);
                    -webkit-mask-size: var(--mask-size,100%);
                    mask-size: var(--mask-size,100%);
                    overflow: hidden;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: absolute;
                    top: 0;
                    width: 100%
                }

                .MW5IWV.N3eg0s {
                    clip: rect(0,auto,auto,0)
                }

                .MW5IWV .Kv1aVt {
                    height: 100%;
                    position: absolute;
                    top: 0;
                    width: 100%
                }

                .MW5IWV .dLPlxY {
                    height: var(--fill-layer-image-height,100%);
                    opacity: var(--fill-layer-image-opacity)
                }

                .MW5IWV .dLPlxY img {
                    height: 100%;
                    width: 100%
                }

                @supports(-webkit-hyphens: none) {
                    .MW5IWV.N3eg0s {
                        clip:auto;
                        -webkit-clip-path: inset(0)
                    }
                }

                .VgO9Yg {
                    height: 100%
                }

                .LWbAav {
                    background-color: var(--bg-overlay-color);
                    background-image: var(--bg-gradient);
                    transition: var(--inherit-transition)
                }

                .K_YxMd,.yK6aSC {
                    opacity: var(--fill-layer-video-opacity)
                }

                .NGjcJN {
                    bottom: var(--media-padding-bottom);
                    height: var(--media-padding-height);
                    position: absolute;
                    top: var(--media-padding-top);
                    width: 100%
                }

                .mNGsUM {
                    transform: scale(var(--scale,1));
                    transition: var(--transform-duration,transform 0s)
                }

                .K_YxMd {
                    height: 100%;
                    position: relative;
                    width: 100%
                }

                wix-media-canvas {
                    display: block;
                    height: 100%
                }

                .I8xA4L {
                    opacity: var(--fill-layer-video-opacity,var(--fill-layer-image-opacity,1))
                }

                .I8xA4L .K_YxMd,.I8xA4L .dLPlxY,.I8xA4L .yK6aSC {
                    opacity: 1
                }

                .Oqnisf {
                    overflow: visible
                }

                .Oqnisf>.MW5IWV .LWbAav {
                    background-color: var(--section-corvid-background-color,var(--bg-overlay-color))
                }

                .cM88eO {
                    backface-visibility: hidden
                }

                .YtfWHd {
                    left: 0;
                    position: absolute;
                    top: 0
                }

                .HlRz5e {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .HlRz5e img {
                    max-width: var(--wix-img-max-width,100%)
                }

                .HlRz5e[data-animate-blur] img {
                    filter: blur(9px);
                    transition: filter .8s ease-in
                }

                .HlRz5e[data-animate-blur] img[data-load-done] {
                    filter: none
                }

                .I5zqsT {
                    display: block;
                    height: 100%;
                    width: 100%
                }

                .bX9O_S {
                    clip-path: var(--fill-layer-clip)
                }

                .Z_wCwr,.bX9O_S {
                    position: absolute;
                    top: 0
                }

                .Jxk_UL img,.Z_wCwr,.bX9O_S {
                    height: 100%;
                    width: 100%
                }

                .K8MSra {
                    opacity: 0
                }

                .K8MSra,.YTb3b4 {
                    position: absolute;
                    top: 0
                }

                .YTb3b4 {
                    height: 0;
                    left: 0;
                    overflow: hidden;
                    width: 0
                }

                .SUz0WK {
                    left: 0;
                    pointer-events: var(--fill-layer-background-media-pointer-events);
                    position: var(--fill-layer-background-media-position)
                }

                .FNxOn5,.SUz0WK,.m4khSP {
                    height: 100%;
                    top: 0;
                    width: 100%
                }

                .FNxOn5 {
                    position: absolute
                }

                .m4khSP {
                    background-color: var(--fill-layer-background-overlay-color);
                    opacity: var(--fill-layer-background-overlay-blend-opacity-fallback,1);
                    position: var(--fill-layer-background-overlay-position);
                    transform: var(--fill-layer-background-overlay-transform)
                }

                @supports(mix-blend-mode: overlay) {
                    .m4khSP {
                        mix-blend-mode:var(--fill-layer-background-overlay-blend-mode);
                        opacity: var(--fill-layer-background-overlay-blend-opacity,1)
                    }
                }

                .dkukWC {
                    --divider-pin-height__: min(1,calc(var(--divider-layers-pin-factor__) + 1));
                    --divider-pin-layer-height__: var(--divider-layers-pin-factor__);
                    --divider-pin-border__: min(1,calc(var(--divider-layers-pin-factor__) / -1 + 1));
                    height: calc(var(--divider-height__) + var(--divider-pin-height__)*var(--divider-layers-size__)*var(--divider-layers-y__))
                }

                .dkukWC,.dkukWC .FRCqDF {
                    left: 0;
                    position: absolute;
                    width: 100%
                }

                .dkukWC .FRCqDF {
                    --divider-layer-i__: var(--divider-layer-i,0);
                    background-position: left calc(50% + var(--divider-offset-x__) + var(--divider-layers-x__)*var(--divider-layer-i__)) bottom;
                    background-repeat: repeat-x;
                    border-bottom-style: solid;
                    border-bottom-width: calc(var(--divider-pin-border__)*var(--divider-layer-i__)*var(--divider-layers-y__));
                    height: calc(var(--divider-height__) + var(--divider-pin-layer-height__)*var(--divider-layer-i__)*var(--divider-layers-y__));
                    opacity: calc(1 - var(--divider-layer-i__)/(var(--divider-layer-i__) + 1))
                }

                .xnZvZH {
                    --divider-height__: var(--divider-top-height,auto);
                    --divider-offset-x__: var(--divider-top-offset-x,0px);
                    --divider-layers-size__: var(--divider-top-layers-size,0);
                    --divider-layers-y__: var(--divider-top-layers-y,0px);
                    --divider-layers-x__: var(--divider-top-layers-x,0px);
                    --divider-layers-pin-factor__: var(--divider-top-layers-pin-factor,0);
                    border-top: var(--divider-top-padding,0) solid var(--divider-top-color,currentColor);
                    opacity: var(--divider-top-opacity,1);
                    top: 0;
                    transform: var(--divider-top-flip,scaleY(-1))
                }

                .xnZvZH .FRCqDF {
                    background-image: var(--divider-top-image,none);
                    background-size: var(--divider-top-size,contain);
                    border-color: var(--divider-top-color,currentColor);
                    bottom: 0;
                    filter: var(--divider-top-filter,none)
                }

                .xnZvZH .FRCqDF[data-divider-layer="1"] {
                    display: var(--divider-top-layer-1-display,block)
                }

                .xnZvZH .FRCqDF[data-divider-layer="2"] {
                    display: var(--divider-top-layer-2-display,block)
                }

                .xnZvZH .FRCqDF[data-divider-layer="3"] {
                    display: var(--divider-top-layer-3-display,block)
                }

                .MBOSCN {
                    --divider-height__: var(--divider-bottom-height,auto);
                    --divider-offset-x__: var(--divider-bottom-offset-x,0px);
                    --divider-layers-size__: var(--divider-bottom-layers-size,0);
                    --divider-layers-y__: var(--divider-bottom-layers-y,0px);
                    --divider-layers-x__: var(--divider-bottom-layers-x,0px);
                    --divider-layers-pin-factor__: var(--divider-bottom-layers-pin-factor,0);
                    border-bottom: var(--divider-bottom-padding,0) solid var(--divider-bottom-color,currentColor);
                    bottom: 0;
                    opacity: var(--divider-bottom-opacity,1);
                    transform: var(--divider-bottom-flip,none)
                }

                .MBOSCN .FRCqDF {
                    background-image: var(--divider-bottom-image,none);
                    background-size: var(--divider-bottom-size,contain);
                    border-color: var(--divider-bottom-color,currentColor);
                    bottom: 0;
                    filter: var(--divider-bottom-filter,none)
                }

                .MBOSCN .FRCqDF[data-divider-layer="1"] {
                    display: var(--divider-bottom-layer-1-display,block)
                }

                .MBOSCN .FRCqDF[data-divider-layer="2"] {
                    display: var(--divider-bottom-layer-2-display,block)
                }

                .MBOSCN .FRCqDF[data-divider-layer="3"] {
                    display: var(--divider-bottom-layer-3-display,block)
                }
            </style>
            <title>Home | Author</title>
            <meta name="description" content="Amüre W. Anat (Venezuela, 1996) Is the author of Dear God, King David is Dead, and painter of Amame.
"/>
            <link rel="canonical" href="https://aishtapamura.wixsite.com/author"/>
            <meta property="og:title" content="Home | Author"/>
            <meta property="og:description" content="Amüre W. Anat (Venezuela, 1996) Is the author of Dear God, King David is Dead, and painter of Amame.
"/>
            <meta property="og:url" content="https://aishtapamura.wixsite.com/author"/>
            <meta property="og:site_name" content="Author"/>
            <meta property="og:type" content="website"/>
            <script type="application/ld+json">
                {
                    "@context": "https://schema.org/",
                    "@type": "LocalBusiness",
                    "name": "Amüre W. Anat",
                    "url": "https://aishtapamura.wixsite.com/author",
                    "address": {
                        "@type": "PostalAddress",
                        "addressCountry": "ES",
                        "addressLocality": "Alicante",
                        "addressRegion": "VC"
                    }
                }</script>
            <meta name="twitter:card" content="summary_large_image"/>
            <meta name="twitter:title" content="Home | Author"/>
            <meta name="twitter:description" content="Amüre W. Anat (Venezuela, 1996) Is the author of Dear God, King David is Dead, and painter of Amame.
"/>
            <style id="css_masterPage">
                @font-face {
                    font-family: 'syne';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/syne/v22/8vIH7w4qzmVxm2NL9G78HEZnMg.woff2') format('woff2');
                    unicode-range: U+0370-0377, U+037A-037F, U+0384-038A, U+038C, U+038E-03A1, U+03A3-03FF;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'syne';
                    font-style: normal;
                    font-weight: 700;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/syne/v22/8vIH7w4qzmVxm2NL9G78HEZnMg.woff2') format('woff2');
                    unicode-range: U+0370-0377, U+037A-037F, U+0384-038A, U+038C, U+038E-03A1, U+03A3-03FF;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'syne';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/syne/v22/8vIH7w4qzmVxm25L9G78HEZnMg.woff2') format('woff2');
                    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20C0, U+2113, U+2C60-2C7F, U+A720-A7FF;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'syne';
                    font-style: normal;
                    font-weight: 700;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/syne/v22/8vIH7w4qzmVxm25L9G78HEZnMg.woff2') format('woff2');
                    unicode-range: U+0100-02AF, U+0304, U+0308, U+0329, U+1E00-1E9F, U+1EF2-1EFF, U+2020, U+20A0-20AB, U+20AD-20C0, U+2113, U+2C60-2C7F, U+A720-A7FF;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'syne';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/syne/v22/8vIH7w4qzmVxm2BL9G78HEY.woff2') format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'syne';
                    font-style: normal;
                    font-weight: 700;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/syne/v22/8vIH7w4qzmVxm2BL9G78HEY.woff2') format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+0304, U+0308, U+0329, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'din-next-w01-light';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/fonts/v2/eca8b0cd-45d8-43cf-aee7-ca462bc5497c/v1/din-next-w10-light.woff2') format('woff2');
                    unicode-range: U+0401-040C, U+040E-044F, U+0451-045C, U+045E-045F, U+0490-0491, U+2116;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'din-next-w01-light';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/fonts/v2/eca8b0cd-45d8-43cf-aee7-ca462bc5497c/v1/din-next-w02-light.woff2') format('woff2');
                    unicode-range: U+000D, U+0100-010F, U+0111-0130, U+0132-0151, U+0154-015F, U+0162-0177, U+0179-017C, U+01FA-01FF, U+0218-021B, U+0237, U+02C9, U+02D8-02D9, U+02DB, U+02DD, U+0394, U+03A9, U+03C0, U+1E80-1E85, U+1EF2-1EF3, U+2070, U+2074-2079, U+2080-2089, U+2113, U+2126, U+212E, U+2153-2154, U+215B-215E, U+2202, U+2206, U+220F, U+2211-2212, U+2215, U+2219-221A, U+221E, U+222B, U+2248, U+2260, U+2264-2265, U+25CA, U+F8FF, U+FB00-FB04;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'din-next-w01-light';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/fonts/v2/eca8b0cd-45d8-43cf-aee7-ca462bc5497c/v1/din-next-w01-light.woff2') format('woff2');
                    unicode-range: U+0020-007E, U+00A0-00FF, U+0110, U+0131, U+0152-0153, U+0160-0161, U+0178, U+017D-017E, U+0192, U+02C6-02C7, U+02DA, U+02DC, U+03BC, U+2013-2014, U+2018-201A, U+201C-201E, U+2020-2022, U+2026, U+2030, U+2039-203A, U+2044, U+20AC, U+2122;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'questrial';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/tag-bundler/api/v1/fonts-cache/googlefont/woff2/s/questrial/v9/QdVUSTchPBm7nuUeVf70viFluW44JQ.woff2') format('woff2');
                    unicode-range: U+0000-00FF, U+0131, U+0152-0153, U+02BB-02BC, U+02C6, U+02DA, U+02DC, U+2000-206F, U+2074, U+20AC, U+2122, U+2191, U+2193, U+2212, U+2215, U+FEFF, U+FFFD;
                    font-display: swap;
                }

                #masterPage:not(.landingPage) #PAGES_CONTAINER {
                    margin-top: 0px;
                    margin-bottom: 0px;
                }

                #masterPage.landingPage #SITE_HEADER {
                    display: none;
                }

                #masterPage.landingPage #SITE_FOOTER {
                    display: none;
                }

                #masterPage.landingPage #SITE_HEADER-placeholder {
                    display: none;
                }

                #masterPage.landingPage #SITE_FOOTER-placeholder {
                    display: none;
                }

                #SITE_CONTAINER.focus-ring-active :not(.has-custom-focus):not(.ignore-focus):not([tabindex="-1"]):focus, #SITE_CONTAINER.focus-ring-active :not(.has-custom-focus):not(.ignore-focus):not([tabindex="-1"]):focus ~ .wixSdkShowFocusOnSibling {
                    --focus-ring-box-shadow: 0 0 0 1px #ffffff, 0 0 0 3px #116dff;
                    box-shadow: var(--focus-ring-box-shadow) !important;
                    z-index: 1;
                }

                .has-inner-focus-ring {
                    --focus-ring-box-shadow: inset 0 0 0 1px #ffffff, inset 0 0 0 3px #116dff !important;
                }

                #masterPage {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                #SITE_HEADER {
                    --pinned-layer-in-container: 50;
                    --above-all-in-container: 49;
                }

                #PAGES_CONTAINER {
                    --pinned-layer-in-container: 51;
                    --above-all-in-container: 49;
                }

                #SITE_FOOTER {
                    --pinned-layer-in-container: 52;
                    --above-all-in-container: 49;
                }

                :root,:host, .spxThemeOverride, .max-width-container {
                    --color_0: 255,255,255;
                    --color_1: 255,255,255;
                    --color_2: 0,0,0;
                    --color_3: 237,28,36;
                    --color_4: 0,136,203;
                    --color_5: 255,203,5;
                    --color_6: 114,114,114;
                    --color_7: 176,176,176;
                    --color_8: 255,255,255;
                    --color_9: 114,114,114;
                    --color_10: 176,176,176;
                    --color_11: 238,238,238;
                    --color_12: 255,209,234;
                    --color_13: 119,119,119;
                    --color_14: 60,60,60;
                    --color_15: 0,0,0;
                    --color_16: 250,206,112;
                    --color_17: 255,209,234;
                    --color_18: 0,0,0;
                    --color_19: 117,81,4;
                    --color_20: 232,31,39;
                    --color_21: 255,190,182;
                    --color_22: 255,157,146;
                    --color_23: 255,59,37;
                    --color_24: 170,39,25;
                    --color_25: 85,20,12;
                    --color_26: 188,235,237;
                    --color_27: 167,216,217;
                    --color_28: 128,216,218;
                    --color_29: 42,145,146;
                    --color_30: 19,84,84;
                    --color_31: 233,179,255;
                    --color_32: 223,141,255;
                    --color_33: 190,26,255;
                    --color_34: 127,17,170;
                    --color_35: 63,9,85;
                    --color_36: 238,238,238;
                    --color_37: 0,0,0;
                    --color_38: 179,179,179;
                    --color_39: 119,119,119;
                    --color_40: 60,60,60;
                    --color_41: 187,36,35;
                    --color_42: 255,209,234;
                    --color_43: 232,31,39;
                    --color_44: 255,100,186;
                    --color_45: 0,0,0;
                    --color_46: 0,0,0;
                    --color_47: 0,0,0;
                    --color_48: 187,36,35;
                    --color_49: 187,36,35;
                    --color_50: 238,238,238;
                    --color_51: 238,238,238;
                    --color_52: 187,36,35;
                    --color_53: 187,36,35;
                    --color_54: 60,60,60;
                    --color_55: 60,60,60;
                    --color_56: 179,179,179;
                    --color_57: 238,238,238;
                    --color_58: 187,36,35;
                    --color_59: 187,36,35;
                    --color_60: 187,36,35;
                    --color_61: 187,36,35;
                    --color_62: 238,238,238;
                    --color_63: 60,60,60;
                    --color_64: 60,60,60;
                    --color_65: 179,179,179;
                    --font_0: normal normal normal 100px/1.4em syne,sans-serif;
                    --font_1: normal normal normal 16px/1.4em din-next-w01-light,sans-serif;
                    --font_2: normal normal normal 42px/1.4em syne,sans-serif;
                    --font_3: normal normal normal 26px/normal syne,sans-serif;
                    --font_4: normal normal normal 22px/normal syne,sans-serif;
                    --font_5: normal normal normal 18px/normal syne,sans-serif;
                    --font_6: normal normal normal 18px/1.4em syne,sans-serif;
                    --font_7: normal normal normal 22px/1.4em questrial,sans-serif;
                    --font_8: normal normal normal 16px/1.4em questrial,sans-serif;
                    --font_9: normal normal normal 13px/1.4em questrial,sans-serif;
                    --font_10: normal normal normal 12px/1.4em din-next-w01-light,sans-serif;
                    --wix-ads-height: 50px;
                    --sticky-offset: 50px;
                    --wix-ads-top-height: 50px;
                    --site-width: 980px;
                    --above-all-z-index: 100000;
                    --portals-z-index: 100001;
                    -webkit-font-smoothing: antialiased;
                    -moz-osx-font-smoothing: grayscale;
                    --minViewportSize: 320;
                    --maxViewportSize: 1920;
                    --theme-spx-ratio: 1px;
                    --scaling-factor: min((100 * var(--one-unit)), var(--section-max-width));
                    --customScaleViewportLimit: clamp(var(--minViewportSize) * 1px, 100 * var(--one-unit), min(var(--section-max-width), var(--maxViewportSize) * 1px));
                }

                .font_0 {
                    font: var(--font_0);
                    color: rgb(var(--color_45));
                    letter-spacing: 0em;
                }

                .font_1 {
                    font: var(--font_1);
                    color: rgb(var(--color_14));
                    letter-spacing: 0em;
                }

                .font_2 {
                    font: var(--font_2);
                    color: rgb(var(--color_45));
                    letter-spacing: 0em;
                }

                .font_3 {
                    font: var(--font_3);
                    color: rgb(var(--color_45));
                    letter-spacing: 0em;
                }

                .font_4 {
                    font: var(--font_4);
                    color: rgb(var(--color_45));
                    letter-spacing: 0em;
                }

                .font_5 {
                    font: var(--font_5);
                    color: rgb(var(--color_45));
                    letter-spacing: 0em;
                }

                .font_6 {
                    font: var(--font_6);
                    color: rgb(var(--color_45));
                    letter-spacing: 0em;
                }

                .font_7 {
                    font: var(--font_7);
                    color: rgb(var(--color_15));
                    letter-spacing: 0em;
                }

                .font_8 {
                    font: var(--font_8);
                    color: rgb(var(--color_15));
                    letter-spacing: 0em;
                }

                .font_9 {
                    font: var(--font_9);
                    color: rgb(var(--color_15));
                    letter-spacing: 0em;
                }

                .font_10 {
                    font: var(--font_10);
                    color: rgb(var(--color_14));
                    letter-spacing: 0em;
                }

                .color_0 {
                    color: rgb(var(--color_0));
                }

                .color_1 {
                    color: rgb(var(--color_1));
                }

                .color_2 {
                    color: rgb(var(--color_2));
                }

                .color_3 {
                    color: rgb(var(--color_3));
                }

                .color_4 {
                    color: rgb(var(--color_4));
                }

                .color_5 {
                    color: rgb(var(--color_5));
                }

                .color_6 {
                    color: rgb(var(--color_6));
                }

                .color_7 {
                    color: rgb(var(--color_7));
                }

                .color_8 {
                    color: rgb(var(--color_8));
                }

                .color_9 {
                    color: rgb(var(--color_9));
                }

                .color_10 {
                    color: rgb(var(--color_10));
                }

                .color_11 {
                    color: rgb(var(--color_11));
                }

                .color_12 {
                    color: rgb(var(--color_12));
                }

                .color_13 {
                    color: rgb(var(--color_13));
                }

                .color_14 {
                    color: rgb(var(--color_14));
                }

                .color_15 {
                    color: rgb(var(--color_15));
                }

                .color_16 {
                    color: rgb(var(--color_16));
                }

                .color_17 {
                    color: rgb(var(--color_17));
                }

                .color_18 {
                    color: rgb(var(--color_18));
                }

                .color_19 {
                    color: rgb(var(--color_19));
                }

                .color_20 {
                    color: rgb(var(--color_20));
                }

                .color_21 {
                    color: rgb(var(--color_21));
                }

                .color_22 {
                    color: rgb(var(--color_22));
                }

                .color_23 {
                    color: rgb(var(--color_23));
                }

                .color_24 {
                    color: rgb(var(--color_24));
                }

                .color_25 {
                    color: rgb(var(--color_25));
                }

                .color_26 {
                    color: rgb(var(--color_26));
                }

                .color_27 {
                    color: rgb(var(--color_27));
                }

                .color_28 {
                    color: rgb(var(--color_28));
                }

                .color_29 {
                    color: rgb(var(--color_29));
                }

                .color_30 {
                    color: rgb(var(--color_30));
                }

                .color_31 {
                    color: rgb(var(--color_31));
                }

                .color_32 {
                    color: rgb(var(--color_32));
                }

                .color_33 {
                    color: rgb(var(--color_33));
                }

                .color_34 {
                    color: rgb(var(--color_34));
                }

                .color_35 {
                    color: rgb(var(--color_35));
                }

                .color_36 {
                    color: rgb(var(--color_36));
                }

                .color_37 {
                    color: rgb(var(--color_37));
                }

                .color_38 {
                    color: rgb(var(--color_38));
                }

                .color_39 {
                    color: rgb(var(--color_39));
                }

                .color_40 {
                    color: rgb(var(--color_40));
                }

                .color_41 {
                    color: rgb(var(--color_41));
                }

                .color_42 {
                    color: rgb(var(--color_42));
                }

                .color_43 {
                    color: rgb(var(--color_43));
                }

                .color_44 {
                    color: rgb(var(--color_44));
                }

                .color_45 {
                    color: rgb(var(--color_45));
                }

                .color_46 {
                    color: rgb(var(--color_46));
                }

                .color_47 {
                    color: rgb(var(--color_47));
                }

                .color_48 {
                    color: rgb(var(--color_48));
                }

                .color_49 {
                    color: rgb(var(--color_49));
                }

                .color_50 {
                    color: rgb(var(--color_50));
                }

                .color_51 {
                    color: rgb(var(--color_51));
                }

                .color_52 {
                    color: rgb(var(--color_52));
                }

                .color_53 {
                    color: rgb(var(--color_53));
                }

                .color_54 {
                    color: rgb(var(--color_54));
                }

                .color_55 {
                    color: rgb(var(--color_55));
                }

                .color_56 {
                    color: rgb(var(--color_56));
                }

                .color_57 {
                    color: rgb(var(--color_57));
                }

                .color_58 {
                    color: rgb(var(--color_58));
                }

                .color_59 {
                    color: rgb(var(--color_59));
                }

                .color_60 {
                    color: rgb(var(--color_60));
                }

                .color_61 {
                    color: rgb(var(--color_61));
                }

                .color_62 {
                    color: rgb(var(--color_62));
                }

                .color_63 {
                    color: rgb(var(--color_63));
                }

                .color_64 {
                    color: rgb(var(--color_64));
                }

                .color_65 {
                    color: rgb(var(--color_65));
                }

                .backcolor_0 {
                    background-color: rgb(var(--color_0));
                }

                .backcolor_1 {
                    background-color: rgb(var(--color_1));
                }

                .backcolor_2 {
                    background-color: rgb(var(--color_2));
                }

                .backcolor_3 {
                    background-color: rgb(var(--color_3));
                }

                .backcolor_4 {
                    background-color: rgb(var(--color_4));
                }

                .backcolor_5 {
                    background-color: rgb(var(--color_5));
                }

                .backcolor_6 {
                    background-color: rgb(var(--color_6));
                }

                .backcolor_7 {
                    background-color: rgb(var(--color_7));
                }

                .backcolor_8 {
                    background-color: rgb(var(--color_8));
                }

                .backcolor_9 {
                    background-color: rgb(var(--color_9));
                }

                .backcolor_10 {
                    background-color: rgb(var(--color_10));
                }

                .backcolor_11 {
                    background-color: rgb(var(--color_11));
                }

                .backcolor_12 {
                    background-color: rgb(var(--color_12));
                }

                .backcolor_13 {
                    background-color: rgb(var(--color_13));
                }

                .backcolor_14 {
                    background-color: rgb(var(--color_14));
                }

                .backcolor_15 {
                    background-color: rgb(var(--color_15));
                }

                .backcolor_16 {
                    background-color: rgb(var(--color_16));
                }

                .backcolor_17 {
                    background-color: rgb(var(--color_17));
                }

                .backcolor_18 {
                    background-color: rgb(var(--color_18));
                }

                .backcolor_19 {
                    background-color: rgb(var(--color_19));
                }

                .backcolor_20 {
                    background-color: rgb(var(--color_20));
                }

                .backcolor_21 {
                    background-color: rgb(var(--color_21));
                }

                .backcolor_22 {
                    background-color: rgb(var(--color_22));
                }

                .backcolor_23 {
                    background-color: rgb(var(--color_23));
                }

                .backcolor_24 {
                    background-color: rgb(var(--color_24));
                }

                .backcolor_25 {
                    background-color: rgb(var(--color_25));
                }

                .backcolor_26 {
                    background-color: rgb(var(--color_26));
                }

                .backcolor_27 {
                    background-color: rgb(var(--color_27));
                }

                .backcolor_28 {
                    background-color: rgb(var(--color_28));
                }

                .backcolor_29 {
                    background-color: rgb(var(--color_29));
                }

                .backcolor_30 {
                    background-color: rgb(var(--color_30));
                }

                .backcolor_31 {
                    background-color: rgb(var(--color_31));
                }

                .backcolor_32 {
                    background-color: rgb(var(--color_32));
                }

                .backcolor_33 {
                    background-color: rgb(var(--color_33));
                }

                .backcolor_34 {
                    background-color: rgb(var(--color_34));
                }

                .backcolor_35 {
                    background-color: rgb(var(--color_35));
                }

                .backcolor_36 {
                    background-color: rgb(var(--color_36));
                }

                .backcolor_37 {
                    background-color: rgb(var(--color_37));
                }

                .backcolor_38 {
                    background-color: rgb(var(--color_38));
                }

                .backcolor_39 {
                    background-color: rgb(var(--color_39));
                }

                .backcolor_40 {
                    background-color: rgb(var(--color_40));
                }

                .backcolor_41 {
                    background-color: rgb(var(--color_41));
                }

                .backcolor_42 {
                    background-color: rgb(var(--color_42));
                }

                .backcolor_43 {
                    background-color: rgb(var(--color_43));
                }

                .backcolor_44 {
                    background-color: rgb(var(--color_44));
                }

                .backcolor_45 {
                    background-color: rgb(var(--color_45));
                }

                .backcolor_46 {
                    background-color: rgb(var(--color_46));
                }

                .backcolor_47 {
                    background-color: rgb(var(--color_47));
                }

                .backcolor_48 {
                    background-color: rgb(var(--color_48));
                }

                .backcolor_49 {
                    background-color: rgb(var(--color_49));
                }

                .backcolor_50 {
                    background-color: rgb(var(--color_50));
                }

                .backcolor_51 {
                    background-color: rgb(var(--color_51));
                }

                .backcolor_52 {
                    background-color: rgb(var(--color_52));
                }

                .backcolor_53 {
                    background-color: rgb(var(--color_53));
                }

                .backcolor_54 {
                    background-color: rgb(var(--color_54));
                }

                .backcolor_55 {
                    background-color: rgb(var(--color_55));
                }

                .backcolor_56 {
                    background-color: rgb(var(--color_56));
                }

                .backcolor_57 {
                    background-color: rgb(var(--color_57));
                }

                .backcolor_58 {
                    background-color: rgb(var(--color_58));
                }

                .backcolor_59 {
                    background-color: rgb(var(--color_59));
                }

                .backcolor_60 {
                    background-color: rgb(var(--color_60));
                }

                .backcolor_61 {
                    background-color: rgb(var(--color_61));
                }

                .backcolor_62 {
                    background-color: rgb(var(--color_62));
                }

                .backcolor_63 {
                    background-color: rgb(var(--color_63));
                }

                .backcolor_64 {
                    background-color: rgb(var(--color_64));
                }

                .backcolor_65 {
                    background-color: rgb(var(--color_65));
                }

                #masterPage:not(.landingPage) {
                    --top-offset: 0px;
                    --header-height: 64px;
                }

                #masterPage.landingPage {
                    --top-offset: 0px;
                }

                #SITE_HEADER {
                    --boxShadowToggleOn-shd: none;
                    --shd: 0.00px 1.00px 4px 0px rgba(0,0,0,0.6);
                    --alpha-brd: 1;
                    --brd: var(--color_11);
                    --backdrop-filter: none;
                    --rd: 0px 0px 0px 0px;
                    --brwt: 0px;
                    --brwb: 0px;
                }

                #SITE_HEADER {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                [data-mesh-id=SITE_HEADERinlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=SITE_HEADERinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=SITE_HEADERinlineContent-gridContainer] > [id="comp-kj9svnyb"] {
                    position: relative;
                    margin: 0px 0px 0px calc((100% - 980px) * 0.5);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                #SITE_HEADER {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                }

                #comp-kj9svnyb {
                    margin-left: auto;
                    margin-right: auto;
                    width: calc(100% - 40px - 40px);
                    min-width: 980px;
                }

                [data-mesh-id=comp-kj9svo67inlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-kj9svo67inlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-kj9svo67inlineContent-gridContainer] > [id="comp-kjcoigli"] {
                    position: relative;
                    margin: 24px 0px 15px calc((100% - 392px) * 0);
                    left: 2px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9svo67inlineContent-gridContainer] > [id="comp-kjcog6xb"] {
                    position: relative;
                    margin: 24px 0px 13px calc((100% - 392px) * 0);
                    left: 39px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9svo67inlineContent-gridContainer] > [id="comp-kjcohe65"] {
                    position: relative;
                    margin: 28px 0px 19px calc((100% - 392px) * 0);
                    left: 218px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9sw3nainlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-kj9sw3nainlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-kj9sw3nainlineContent-gridContainer] > [id="comp-kj9sx3ul"] {
                    position: relative;
                    margin: 26px 0px 14px calc((100% - 588px) * 1);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                #comp-kj9svnyb {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    --padding: 0px;
                    --margin: 0px;
                    min-width: 980px;
                    --firstChildMarginTop: -1px;
                    --lastChildMarginBottom: -1px;
                    --items-direction: row;
                }

                #comp-kj9svo67 {
                    width: 392px;
                }

                #comp-kj9svo67 {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    width: 100%;
                    --column-width: 392px;
                    --column-flex: 392;
                }

                #comp-kjcoigli {
                    width: 25px;
                    height: 25px;
                }

                #comp-kjcoigli {
                    --fill-opacity: 1;
                    --stroke-width: 0;
                    --stroke: #000000;
                    --stroke-opacity: 1;
                    --fill: #FFD1EA;
                }

                #comp-kjcog6xb {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kjcog6xb {
                    width: 180px;
                    height: auto;
                }

                #comp-kjcohe65 {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kjcohe65 {
                    width: 208px;
                    height: auto;
                }

                #comp-kj9sw3na {
                    width: 588px;
                }

                #comp-kj9sw3na {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    width: 100%;
                    --column-width: 588px;
                    --column-flex: 588;
                }

                #comp-kj9sx3ul {
                    --menuTotalBordersX: 0px;
                    --menuTotalBordersY: 0px;
                    --bgDrop: var(--color_11);
                    --rd: 0px;
                    --shd: none;
                    --fnt: var(--font_8);
                    --sep: var(--color_37);
                    --txt: var(--color_15);
                    --alpha-txt: 1;
                    --trans: color 0.4s ease 0s;
                    --pad: 5px;
                    --txth: var(--color_18);
                    --alpha-txth: 1;
                    --txts: var(--color_18);
                    --alpha-txts: 1;
                    --alpha-sep: 1;
                    --alpha-bgDrop: 1;
                    --boxShadowToggleOn-shd: none;
                }

                #comp-kj9sx3ul {
                    width: 588px;
                    height: 24px;
                }

                #comp-kj9sx3ul {
                    --menuTotalBordersY: 0px;
                    --menuTotalBordersX: 0px;
                }

                #PAGES_CONTAINER {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                #SITE_PAGES {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                #SITE_PAGES {
                    --transition-duration: 700ms;
                }

                #SITE_FOOTER {
                    --boxShadowToggleOn-shd: none;
                    --shd: 0.00px 1.00px 4px 0px rgba(0,0,0,0.6);
                    --alpha-brd: 1;
                    --brd: var(--color_11);
                    --backdrop-filter: none;
                    --rd: 0px 0px 0px 0px;
                    --brwt: 0px;
                    --brwb: 0px;
                }

                #SITE_FOOTER {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                [data-mesh-id=SITE_FOOTERinlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=SITE_FOOTERinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: min-content 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=SITE_FOOTERinlineContent-gridContainer] > [id="comp-kjcp8qvu"] {
                    position: relative;
                    margin: 10px 40px 26px 40px;
                    left: 0;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: stretch;
                    align-self: start;
                }

                [data-mesh-id=SITE_FOOTERinlineContent-gridContainer] > [id="comp-kj9u5y5z"] {
                    position: relative;
                    margin: 0px 0px 45px calc((100% - 980px) * 0.5);
                    left: 0px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start;
                }

                #SITE_FOOTER {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                }

                #comp-kjcp8qvu {
                    --lnw: 1px;
                    --brd: var(--color_47);
                    --alpha-brd: 1;
                }

                #comp-kjcp8qvu {
                    width: calc(100% - 40px - 40px);
                    left: 0;
                    margin-left: 40px;
                    min-width: initial;
                    height: 5px;
                }

                #comp-kjcp8qvu {
                    transform-origin: center 0.5px;
                }

                #comp-kj9u5y5z {
                    margin-left: auto;
                    margin-right: auto;
                    width: calc(100% - 40px - 40px);
                    min-width: 980px;
                }

                [data-mesh-id=comp-kj9u5ybjinlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-kj9u5ybjinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 158px;
                    grid-template-rows: min-content 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-kj9u5ybjinlineContent-gridContainer] > [id="comp-kjcp7mwn"] {
                    position: relative;
                    margin: 12px 0px 7px calc((100% - 245px) * 0);
                    left: 10px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9u5ybjinlineContent-gridContainer] > [id="comp-kj9u7gc8"] {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 245px) * 0);
                    left: 10px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9u6b1ainlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-kj9u6b1ainlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 158px;
                    grid-template-rows: min-content 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-kj9u6b1ainlineContent-gridContainer] > [id="comp-kjcp7w67"] {
                    position: relative;
                    margin: 12px 0px 7px calc((100% - 245px) * 0.5);
                    left: 7px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9u6b1ainlineContent-gridContainer] > [id="comp-kj9u7jfm"] {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 245px) * 0.5);
                    left: 7px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9u6e6ninlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-kj9u6e6ninlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 158px;
                    grid-template-rows: min-content 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-kj9u6e6ninlineContent-gridContainer] > [id="comp-kjcp5ldh"] {
                    position: relative;
                    margin: 12px 0px 8px calc((100% - 245px) * 1);
                    left: 9px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kj9u6e6ninlineContent-gridContainer] > [id="comp-kjcp46jj"] {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 245px) * 1);
                    left: 7px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-kjcktbwbinlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-kjcktbwbinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 158px;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-kjcktbwbinlineContent-gridContainer] > [id="comp-kjcktbxp"] {
                    position: relative;
                    margin: 27px 0px 10px calc((100% - 245px) * 1);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                #comp-kj9u5y5z {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    --padding: 0px;
                    --margin: 0px;
                    min-width: 980px;
                    --firstChildMarginTop: -1px;
                    --lastChildMarginBottom: -1px;
                    --items-direction: row;
                }

                #comp-kj9u5ybj {
                    width: 245px;
                }

                #comp-kj9u5ybj {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    width: 100%;
                    --column-width: 245px;
                    --column-flex: 245;
                }

                #comp-kjcp7mwn {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kjcp7mwn {
                    width: 187px;
                    height: auto;
                }

                #comp-kj9u7gc8 {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kj9u7gc8 {
                    width: 187px;
                    height: auto;
                }

                #comp-kj9u6b1a {
                    width: 245px;
                }

                #comp-kj9u6b1a {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    width: 100%;
                    --column-width: 245px;
                    --column-flex: 245;
                }

                #comp-kjcp7w67 {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kjcp7w67 {
                    width: 187px;
                    height: auto;
                }

                #comp-kj9u7jfm {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kj9u7jfm {
                    width: 192px;
                    height: auto;
                }

                #comp-kj9u6e6n {
                    width: 245px;
                }

                #comp-kj9u6e6n {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    width: 100%;
                    --column-width: 245px;
                    --column-flex: 245;
                }

                #comp-kjcp5ldh {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kjcp5ldh {
                    width: 187px;
                    height: auto;
                }

                #comp-kjcp46jj {
                    width: 55px;
                    height: 24px;
                }

                #comp-kjcp46jj {
                    --item-size: 24px;
                    --item-margin: 0px 7px 0px 0px;
                    --item-display: inline-block;
                    width: 55px;
                    height: 24px;
                }

                #comp-kjcktbwb {
                    width: 245px;
                }

                #comp-kjcktbwb {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    width: 100%;
                    --column-width: 245px;
                    --column-flex: 245;
                }

                #comp-kjcktbxp {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                #comp-kjcktbxp {
                    width: 131px;
                    height: auto;
                }
            </style>
            <style id="css_c1dmp">
                @font-face {
                    font-family: 'avenir-lt-w01_85-heavy1475544';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/fonts/v2/74290729-59ae-4129-87d0-2eec3974dce1/v1/avenir-lt-w05_85-heavy.woff2') format('woff2');
                    unicode-range: U+0100-012B, U+012E-0130, U+0132-0137, U+0139-0149, U+014C-0151, U+0154-015F, U+0162-0177, U+0179-017C, U+0218-021B, U+02C9, U+02D8-02D9, U+02DB, U+02DD, U+0394, U+03A9, U+03BC, U+03C0, U+1E9E, U+20B9-20BA, U+20BC-20BD, U+2113, U+2126, U+212E, U+2202, U+2206, U+220F, U+2211-2212, U+2215, U+2219-221A, U+221E, U+222B, U+2248, U+2260, U+2264-2265, U+25CA, U+F8FF, U+FB01-FB02;
                    font-display: swap;
                }

                @font-face {
                    font-family: 'avenir-lt-w01_85-heavy1475544';
                    font-style: normal;
                    font-weight: 400;
                    src: url('//static.parastorage.com/fonts/v2/74290729-59ae-4129-87d0-2eec3974dce1/v1/avenir-lt-w01_85-heavy1475544.woff2') format('woff2');
                    unicode-range: U+0000, U+000D, U+0020-007E, U+00A0-00FF, U+0131, U+0152-0153, U+0160-0161, U+0178, U+017D-017E, U+0192, U+0237, U+02C6-02C7, U+02DA, U+02DC, U+2013-2014, U+2018-201A, U+201C-201E, U+2020-2022, U+2026, U+2030, U+2039-203A, U+2044, U+20AC, U+2122;
                    font-display: swap;
                }

                #c1dmp {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                #masterPage {
                    --pinned-layers-in-page: 0;
                }

                [data-mesh-id=Containerc1dmpinlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=Containerc1dmpinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: 40px;
                    grid-template-rows: 1fr;
                    grid-template-columns: 100%;
                    padding-bottom: 0px;
                    box-sizing: border-box;
                }

                [data-mesh-id=Containerc1dmpinlineContent-gridContainer] > [id="comp-lslo8zdk"] {
                    position: relative;
                    margin: 0px 0px 0 calc((100% - 980px) * 0.5);
                    left: 0px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                #comp-lslo8zdk {
                    left: 0;
                    margin-left: 0;
                    width: 100%;
                    min-width: 0;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent] {
                    height: auto;
                    width: 100%;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] {
                    position: static;
                    display: grid;
                    height: auto;
                    width: 100%;
                    min-height: auto;
                    grid-template-rows: repeat(3, min-content) 1fr;
                    grid-template-columns: 100%;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] > [id="comp-kjcl52y9"] {
                    position: relative;
                    margin: 59px 0px 63px calc((100% - 980px) * 0.5);
                    left: 10px;
                    grid-area: 1 / 1 / 5 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] > [id="comp-kj9sumrm"] {
                    position: relative;
                    margin: 130px 0px 12px calc((100% - 980px) * 0.5);
                    left: 529px;
                    grid-area: 1 / 1 / 2 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] > [id="comp-kj9u78b4"] {
                    position: relative;
                    margin: 0px 0px 65px calc((100% - 980px) * 0.5);
                    left: 529px;
                    grid-area: 2 / 1 / 3 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] > [id="comp-kjcod4ll"] {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 980px) * 0.5);
                    left: 529px;
                    grid-area: 3 / 1 / 4 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] > [id="comp-kjcod5ul"] {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 980px) * 0.5);
                    left: 633px;
                    grid-area: 3 / 1 / 4 / 2;
                    justify-self: start;
                    align-self: start;
                }

                [data-mesh-id=comp-lslo8zdkinlineContent-gridContainer] > [id="comp-kjcocqs6"] {
                    position: relative;
                    margin: 0px 0px 10px calc((100% - 980px) * 0.5);
                    left: 884px;
                    grid-area: 3 / 1 / 4 / 2;
                    justify-self: start;
                    align-self: start;
                }

                #comp-kjcl52y9 {
                    --contentPaddingLeft: 0px;
                    --contentPaddingRight: 0px;
                    --contentPaddingTop: 0px;
                    --contentPaddingBottom: 0px;
                }

                @media (prefers-reduced-motion: no-preference) {
                    #comp-kjcl52y9:not([data-motion-enter="done"]) {
                        opacity: 0;
                    }
                }

                #comp-kjcl52y9 {
                    width: 480px;
                    height: 480px;
                }

                #comp-kj9sumrm {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                @media (prefers-reduced-motion: no-preference) {
                    #comp-kj9sumrm:not([data-motion-enter="done"]) {
                        opacity: 0;
                    }
                }

                #comp-kj9sumrm {
                    width: 349px;
                    height: auto;
                }

                #comp-kj9u78b4 {
                    --backgroundColor: 0,0,0;
                    --alpha-backgroundColor: 0;
                    --blendMode: normal;
                    --textShadow: 0px 0px transparent;
                    --textOutline: 0px 0px transparent;
                }

                @media (prefers-reduced-motion: no-preference) {
                    #comp-kj9u78b4:not([data-motion-enter="done"]) {
                        opacity: 0;
                    }
                }

                #comp-kj9u78b4 {
                    width: 451px;
                    height: auto;
                }

                #comp-kjcod4ll {
                    --rd: 20px;
                    --trans1: border-color 0.4s ease 0s, background-color 0.4s ease 0s;
                    --shd: none;
                    --fnt: normal normal normal 13px/1.4em avenir-lt-w01_85-heavy1475544,sans-serif;
                    --trans2: color 0.4s ease 0s;
                    --txt: 50,50,50;
                    --brw: 2px;
                    --bg: 255,255,255;
                    --brd: 50,50,50;
                    --bgh: 50,50,50;
                    --brdh: 50,50,50;
                    --txth: 255,255,255;
                    --bgd: 204,204,204;
                    --alpha-bgd: 1;
                    --brdd: 204,204,204;
                    --alpha-brdd: 1;
                    --txtd: 255,255,255;
                    --alpha-txtd: 1;
                    --alpha-txth: 1;
                    --alpha-brdh: 0;
                    --alpha-brd: 1;
                    --alpha-bg: 0;
                    --alpha-bgh: 1;
                    --boxShadowToggleOn-shd: none;
                    --alpha-txt: 1;
                }

                @media (prefers-reduced-motion: no-preference) {
                    #comp-kjcod4ll:not([data-motion-enter="done"]) {
                        opacity: 0;
                    }
                }

                #comp-kjcod4ll {
                    width: 96px;
                    height: 81px;
                }

                #comp-kjcod5ul {
                    --rd: 20px;
                    --trans1: border-color 0.4s ease 0s, background-color 0.4s ease 0s;
                    --shd: none;
                    --fnt: normal normal normal 13px/1.4em avenir-lt-w01_85-heavy1475544,sans-serif;
                    --trans2: color 0.4s ease 0s;
                    --txt: 50,50,50;
                    --brw: 2px;
                    --bg: 255,255,255;
                    --brd: 50,50,50;
                    --bgh: 50,50,50;
                    --brdh: 50,50,50;
                    --txth: 255,255,255;
                    --bgd: 204,204,204;
                    --alpha-bgd: 1;
                    --brdd: 204,204,204;
                    --alpha-brdd: 1;
                    --txtd: 255,255,255;
                    --alpha-txtd: 1;
                    --alpha-txth: 1;
                    --alpha-brdh: 0;
                    --alpha-brd: 1;
                    --alpha-bg: 0;
                    --alpha-bgh: 1;
                    --boxShadowToggleOn-shd: none;
                    --alpha-txt: 1;
                }

                @media (prefers-reduced-motion: no-preference) {
                    #comp-kjcod5ul:not([data-motion-enter="done"]) {
                        opacity: 0;
                    }
                }

                #comp-kjcod5ul {
                    width: 245px;
                    height: 81px;
                }

                #comp-kjcocqs6 {
                    --rd: 20px;
                    --trans1: border-color 0.4s ease 0s, background-color 0.4s ease 0s;
                    --shd: none;
                    --fnt: normal normal normal 13px/1.4em avenir-lt-w01_85-heavy1475544,sans-serif;
                    --trans2: color 0.4s ease 0s;
                    --txt: 50,50,50;
                    --brw: 2px;
                    --bg: 255,255,255;
                    --brd: 50,50,50;
                    --bgh: 50,50,50;
                    --brdh: 50,50,50;
                    --txth: 255,255,255;
                    --bgd: 204,204,204;
                    --alpha-bgd: 1;
                    --brdd: 204,204,204;
                    --alpha-brdd: 1;
                    --txtd: 255,255,255;
                    --alpha-txtd: 1;
                    --alpha-txth: 1;
                    --alpha-brdh: 0;
                    --alpha-brd: 1;
                    --alpha-bg: 0;
                    --alpha-bgh: 1;
                    --boxShadowToggleOn-shd: none;
                    --alpha-txt: 1;
                }

                @media (prefers-reduced-motion: no-preference) {
                    #comp-kjcocqs6:not([data-motion-enter="done"]) {
                        opacity: 0;
                    }
                }

                #comp-kjcocqs6 {
                    width: 96px;
                    height: 81px;
                }
            </style>
            <style id="compCssMappers_c1dmp">
                #c1dmp {
                    width: auto;
                    min-height: 40px;
                }

                #pageBackground_c1dmp {
                    --bg-position: absolute;
                    --fill-layer-background-overlay-color: transparent;
                    --fill-layer-background-overlay-position: absolute;
                    --bg-overlay-color: rgb(var(--color_11));
                    --bg-gradient: none;
                }

                #comp-lslo8zdk {
                    --bg-overlay-color: transparent;
                    --bg-gradient: none;
                    min-width: 980px;
                }

                #comp-kjcl52y9 {
                    --height: 480px;
                    --width: 480px;
                    --mask-image: url("data:image/svg+xml,%3Csvg preserveAspectRatio='none' data-bbox='20 20 160 160' viewBox='20 20 160 160' height='200' width='200' xmlns='http://www.w3.org/2000/svg' data-type='shape' style='transform: scale(-1, 1);'%3E%3Cg%3E%3Cpath d='M180 100c0 44.183-35.817 80-80 80s-80-35.817-80-80 35.817-80 80-80 80 35.817 80 80z'/%3E%3C/g%3E%3C/svg%3E%0A");
                    --mask-position: 0% 0%;
                    --mask-size: 100% 100%;
                    --mask-repeat: no-repeat;
                }

                #comp-kjcod4ll {
                    --shc-mutated-brightness: 128,128,128;
                    --margin-start: 0px;
                    --margin-end: 0px;
                    --fnt: normal normal normal 13px/1.4em avenir-lt-w01_85-heavy1475544,sans-serif;
                    --label-align: center;
                    --label-text-align: center;
                }

                #comp-kjcod5ul {
                    --shc-mutated-brightness: 128,128,128;
                    --margin-start: 0px;
                    --margin-end: 0px;
                    --fnt: normal normal normal 13px/1.4em avenir-lt-w01_85-heavy1475544,sans-serif;
                    --label-align: center;
                    --label-text-align: center;
                }

                #comp-kjcocqs6 {
                    --shc-mutated-brightness: 128,128,128;
                    --margin-start: 0px;
                    --margin-end: 0px;
                    --fnt: normal normal normal 13px/1.4em avenir-lt-w01_85-heavy1475544,sans-serif;
                    --label-align: center;
                    --label-text-align: center;
                }
            </style>
        </head>
        <body class=''>
            <script type="text/javascript">
                var bodyCacheable = true;

                var exclusionReason = {
                    "shouldRender": true,
                    "forced": false
                };
                var ssrInfo = {
                    "cacheExclusionReason": "",
                    "renderBodyTime": 405,
                    "renderTimeStamp": 1741596377920
                }
            </script>
            <!--pageHtmlEmbeds.bodyStart start-->
            <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyStart start"></script>
            <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyStart end"></script>
            <!--pageHtmlEmbeds.bodyStart end-->
            <script id="wix-first-paint">
                if (window.ResizeObserver && (!window.PerformanceObserver || !PerformanceObserver.supportedEntryTypes || PerformanceObserver.supportedEntryTypes.indexOf('paint') === -1)) {
                    new ResizeObserver(function(entries, observer) {
                        entries.some(function(entry) {
                            var contentRect = entry.contentRect;
                            if (contentRect.width > 0 && contentRect.height > 0) {
                                requestAnimationFrame(function(now) {
                                    window.wixFirstPaint = now;
                                    dispatchEvent(new CustomEvent('wixFirstPaint'));
                                });
                                observer.disconnect();
                                return true;
                            }
                        });
                    }
                    ).observe(document.body);
                }
            </script>
            <div id="SITE_CONTAINER">
                <div id="main_MF" class="main_MF">
                    <div id="SCROLL_TO_TOP" class="Vd6aQZ ignore-focus SCROLL_TO_TOP" tabindex="-1" role="region" aria-label="top of page">
                        <span class="mHZSwn">top of page</span>
                    </div>
                    <!--$-->
                    <!--/$-->
                    <!--$-->
                    <div id="WIX_ADS" class="EFLBov czJOIz ytGGBw">
                        <a data-testid="linkElement" href="//www.wix.com/lpviral/enviral?utm_campaign=vir_wixad_live&amp;orig_msid=736c7394-4e87-4a3c-9265-7dad8dc29df5&amp;adsVersion=white" target="_blank" rel="nofollow" class="Oxzvyr YD5pSO has-custom-focus">
                            <span class="aGHwBE">
                                <span data-hook="freemium-text" class="areOb6">
                                    This site was designed with the 
                                    <div data-testid="bannerLogo" class="dTTUA9">
                                        <div>
                                            <svg class="_4i7Zy" viewBox="0 0 28 10.89" aria-label="wix">
                                                <path d="M16.02.2c-.55.3-.76.78-.76 2.14a2.17 2.17 0 0 1 .7-.42 3 3 0 0 0 .7-.4A1.62 1.62 0 0 0 17.22 0a3 3 0 0 0-1.18.2z" class="o4sLYL"></path>
                                                <path d="M12.77.52a2.12 2.12 0 0 0-.58 1l-1.5 5.8-1.3-4.75a4.06 4.06 0 0 0-.7-1.55 2.08 2.08 0 0 0-2.9 0 4.06 4.06 0 0 0-.7 1.55L3.9 7.32l-1.5-5.8a2.12 2.12 0 0 0-.6-1A2.6 2.6 0 0 0 0 .02l2.9 10.83a3.53 3.53 0 0 0 1.42-.17c.62-.33.92-.57 1.3-2 .33-1.33 1.26-5.2 1.35-5.47a.5.5 0 0 1 .34-.4.5.5 0 0 1 .4.5c.1.3 1 4.2 1.4 5.5.4 1.5.7 1.7 1.3 2a3.53 3.53 0 0 0 1.4.2l2.8-11a2.6 2.6 0 0 0-1.82.53zm4.43 1.26a1.76 1.76 0 0 1-.58.5c-.26.16-.52.26-.8.4a.82.82 0 0 0-.57.82v7.36a2.47 2.47 0 0 0 1.2-.15c.6-.3.75-.6.75-2V1.8zm7.16 3.68L28 .06a3.22 3.22 0 0 0-2.3.42 8.67 8.67 0 0 0-1 1.24l-1.34 1.93a.3.3 0 0 1-.57 0l-1.4-1.93a8.67 8.67 0 0 0-1-1.24 3.22 3.22 0 0 0-2.3-.43l3.6 5.4-3.7 5.4a3.54 3.54 0 0 0 2.32-.48 7.22 7.22 0 0 0 1-1.16l1.33-1.9a.3.3 0 0 1 .57 0l1.37 2a8.2 8.2 0 0 0 1 1.2 3.47 3.47 0 0 0 2.33.5z"></path>
                                            </svg>
                                        </div>
                                        <div class="uJDaUS">.com</div>
                                    </div>
                                    website builder. Create your website today.
                                </span>
                                <span data-hook="freemium-button" class="O0tKs2 Oxzvyr">Start Now</span>
                            </span>
                        </a>
                    </div>
                    <!--/$-->
                    <!--$-->
                    <div id="BACKGROUND_GROUP" class="backgroundGroup_c1dmp BACKGROUND_GROUP">
                        <div id="BACKGROUND_GROUP_TRANSITION_GROUP">
                            <div id="pageBackground_c1dmp" data-media-height-override-type="" data-media-position-override="false" class="pageBackground_c1dmp BmZ5pC">
                                <div id="bgLayers_pageBackground_c1dmp" data-hook="bgLayers" data-motion-part="BG_LAYER pageBackground_c1dmp" class="MW5IWV">
                                    <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                    <div id="bgMedia_pageBackground_c1dmp" data-motion-part="BG_MEDIA pageBackground_c1dmp" class="VgO9Yg"></div>
                                    <div data-testid="bgOverlay" class="m4khSP"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                    <!--/$-->
                    <div id="site-root" class="overflow-clip-in-mobile site-root">
                        <!--$-->
                        <div id="masterPage" class="mesh-layout overflow-x-clip overflow-x-clip-in-mobile masterPage css-editing-scope">
                            <header id="SITE_HEADER" class="AT7o0U SITE_HEADER wixui-header" tabindex="-1">
                                <div class="lvxhkV"></div>
                                <div class="cKxVkc">
                                    <div class="vlM3HR"></div>
                                    <div class="VrZrC0">
                                        <div data-mesh-id="SITE_HEADERinlineContent" data-testid="inline-content" class="">
                                            <div data-mesh-id="SITE_HEADERinlineContent-gridContainer" data-testid="mesh-container-content">
                                                <!--$-->
                                                <section id="comp-kj9svnyb" class="comp-kj9svnyb CohWsy wixui-column-strip">
                                                    <div id="bgLayers_comp-kj9svnyb" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9svnyb" class="if7Vw2">
                                                        <div data-testid="colorUnderlay" class="tcElKx i1tH8h"></div>
                                                        <div id="bgMedia_comp-kj9svnyb" data-motion-part="BG_MEDIA comp-kj9svnyb" class="wG8dni"></div>
                                                    </div>
                                                    <div data-testid="columns" class="V5AUxf">
                                                        <!--$-->
                                                        <div id="comp-kj9svo67" class="comp-kj9svo67 YzqVVZ wixui-column-strip__column">
                                                            <div id="bgLayers_comp-kj9svo67" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9svo67" class="MW5IWV">
                                                                <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                <div id="bgMedia_comp-kj9svo67" data-motion-part="BG_MEDIA comp-kj9svo67" class="VgO9Yg"></div>
                                                            </div>
                                                            <div data-mesh-id="comp-kj9svo67inlineContent" data-testid="inline-content" class="">
                                                                <div data-mesh-id="comp-kj9svo67inlineContent-gridContainer" data-testid="mesh-container-content">
                                                                    <!--$-->
                                                                    <div id="comp-kjcoigli" class="comp-kjcoigli wixui-vector-image">
                                                                        <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author" target="_self" class="a9YhBi">
                                                                            <div data-testid="svgRoot-comp-kjcoigli" class="AKxYR5 VZYmYf comp-kjcoigli">
                                                                                <svg preserveAspectRatio="none" data-bbox="0 0 200 200" xmlns="http://www.w3.org/2000/svg" width="200" height="200" viewBox="0 0 200 200" role="img" aria-label="Homepage">
                                                                                    <g>
                                                                                        <path d="M200 100c0 55.228-44.772 100-100 100S0 155.228 0 100 44.772 0 100 0s100 44.772 100 100z"/>
                                                                                    </g>
                                                                                </svg>
                                                                            </div>
                                                                        </a>
                                                                    </div>
                                                                    <!--/$-->
                                                                    <!--$-->
                                                                    <div id="comp-kjcog6xb" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kjcog6xb wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_4 wixui-rich-text__text" style="line-height:normal; font-size:22px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">
                                                                                <a href="https://aishtapamura.wixsite.com/author" target="_self" class="wixui-rich-text__text">Am &uuml;re W. Anat</a>
                                                                            </span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                    <!--$-->
                                                                    <div id="comp-kjcohe65" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kjcohe65 wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_8 wixui-rich-text__text" style="line-height:normal; font-size:16px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">Author</span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <!--/$-->
                                                        <!--$-->
                                                        <div id="comp-kj9sw3na" class="comp-kj9sw3na YzqVVZ wixui-column-strip__column">
                                                            <div id="bgLayers_comp-kj9sw3na" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9sw3na" class="MW5IWV">
                                                                <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                <div id="bgMedia_comp-kj9sw3na" data-motion-part="BG_MEDIA comp-kj9sw3na" class="VgO9Yg"></div>
                                                            </div>
                                                            <div data-mesh-id="comp-kj9sw3nainlineContent" data-testid="inline-content" class="">
                                                                <div data-mesh-id="comp-kj9sw3nainlineContent-gridContainer" data-testid="mesh-container-content">
                                                                    <!--$-->
                                                                    <wix-dropdown-menu id="comp-kj9sx3ul" class="nYRjqR GUSTu5 comp-kj9sx3ul wixui-dropdown-menu hidden-during-prewarmup" tabIndex="-1" dir="ltr" data-stretch-buttons-to-menu-width="false" data-same-width-buttons="true" data-num-items="3" data-menuborder-y="0" data-menubtn-border="0" data-ribbon-els="0" data-label-pad="0" data-ribbon-extra="0" data-dropalign="right">
                                                                        <nav class="ONlyPu" id="comp-kj9sx3ulnavContainer" aria-label="Site">
                                                                            <ul class="qDaKPQ" id="comp-kj9sx3ulitemsContainer" style="text-align:right" data-marginallchildren="true">
                                                                                <li id="comp-kj9sx3ul0" data-direction="ltr" data-listposition="center" data-data-id="dataItem-kvsalbhp" data-state="menu false  link" data-index="0" class="JAo9_G wixui-dropdown-menu__item rhHoTC">
                                                                                    <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author/bio" target="_self" class="wIGMae" aria-haspopup="false">
                                                                                        <div class="Zw7XIs">
                                                                                            <div class="" style="text-align:center">
                                                                                                <p class="aWTgIN" style="text-align:center" id="comp-kj9sx3ul0label">Bio</p>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </li>
                                                                                <li id="comp-kj9sx3ul1" data-direction="ltr" data-listposition="center" data-data-id="dataItem-kvsalbhp1" data-state="menu false  link" data-index="1" class="JAo9_G wixui-dropdown-menu__item rhHoTC">
                                                                                    <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author/projects" target="_self" class="wIGMae" aria-haspopup="false">
                                                                                        <div class="Zw7XIs">
                                                                                            <div class="" style="text-align:center">
                                                                                                <p class="aWTgIN" style="text-align:center" id="comp-kj9sx3ul1label">Projects</p>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </li>
                                                                                <li id="comp-kj9sx3ul2" data-direction="ltr" data-listposition="right" data-data-id="dataItem-kvsalbhq" data-state="menu false  link" data-index="2" class="JAo9_G wixui-dropdown-menu__item rhHoTC">
                                                                                    <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author/contact" target="_self" class="wIGMae" aria-haspopup="false">
                                                                                        <div class="Zw7XIs">
                                                                                            <div class="" style="text-align:center">
                                                                                                <p class="aWTgIN" style="text-align:center" id="comp-kj9sx3ul2label">Contact</p>
                                                                                            </div>
                                                                                        </div>
                                                                                    </a>
                                                                                </li>
                                                                                <li id="comp-kj9sx3ul__more__" data-direction="ltr" data-listposition="right" data-state="menu false  header" data-index="__more__" data-dropdown="false" class="XFe7yJ rhHoTC">
                                                                                    <div data-testid="linkElement" class="wIGMae" tabindex="0" aria-haspopup="false">
                                                                                        <div class="Zw7XIs">
                                                                                            <div class="" style="text-align:center">
                                                                                                <p class="aWTgIN" style="text-align:center" id="comp-kj9sx3ul__more__label">More</p>
                                                                                            </div>
                                                                                        </div>
                                                                                    </div>
                                                                                </li>
                                                                            </ul>
                                                                            <div class="A4aeYo" id="comp-kj9sx3uldropWrapper" data-dropalign="right" data-dropdown-shown="false">
                                                                                <ul class="ByVsPT wixui-dropdown-menu__submenu" id="comp-kj9sx3ulmoreContainer"></ul>
                                                                            </div>
                                                                            <div style="display:none" id="comp-kj9sx3ulnavContainer-hiddenA11ySubMenuIndication">Use tab to navigate through the menu items.</div>
                                                                        </nav>
                                                                    </wix-dropdown-menu>
                                                                    <!--/$-->
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <!--/$-->
                                                    </div>
                                                </section>
                                                <!--/$-->
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </header>
                            <main id="PAGES_CONTAINER" class="PAGES_CONTAINER" tabindex="-1" data-main-content="true">
                                <div id="SITE_PAGES" class="JsJXaX SITE_PAGES">
                                    <div id="SITE_PAGES_TRANSITION_GROUP" class="AnQkDU">
                                        <div id="c1dmp" class="dBAkHi c1dmp">
                                            <div class="PFkO7r wixui-page" data-testid="page-bg"></div>
                                            <div class="HT5ybB">
                                                <!--$-->
                                                <div id="Containerc1dmp" class="Containerc1dmp SPY_vo">
                                                    <div data-mesh-id="Containerc1dmpinlineContent" data-testid="inline-content" class="">
                                                        <div data-mesh-id="Containerc1dmpinlineContent-gridContainer" data-testid="mesh-container-content">
                                                            <!--$-->
                                                            <section id="comp-lslo8zdk" tabindex="-1" class="Oqnisf comp-lslo8zdk wixui-section" data-block-level-container="ClassicSection">
                                                                <div id="bgLayers_comp-lslo8zdk" data-hook="bgLayers" data-motion-part="BG_LAYER comp-lslo8zdk" class="MW5IWV">
                                                                    <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                    <div id="bgMedia_comp-lslo8zdk" data-motion-part="BG_MEDIA comp-lslo8zdk" class="VgO9Yg"></div>
                                                                </div>
                                                                <div data-mesh-id="comp-lslo8zdkinlineContent" data-testid="inline-content" class="">
                                                                    <div data-mesh-id="comp-lslo8zdkinlineContent-gridContainer" data-testid="mesh-container-content">
                                                                        <!--$-->
                                                                        <div id="comp-kjcl52y9" class="MazNVa comp-kjcl52y9 wixui-image">
                                                                            <div data-testid="linkElement" class="j7pOnl">
                                                                                <img fetchpriority="high" sizes="480px" srcSet="https://static.wixstatic.com/media/927f01_f82687370ca84fb894c1e9440a54114c~mv2.png/v1/crop/x_0,y_170,w_856,h_856/fill/w_480,h_480,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/Screenshot%202025-03-06%20at%2016_52_09.png 1x, https://static.wixstatic.com/media/927f01_f82687370ca84fb894c1e9440a54114c~mv2.png/v1/crop/x_0,y_170,w_856,h_856/fill/w_856,h_856,al_c,q_90,enc_avif,quality_auto/Screenshot%202025-03-06%20at%2016_52_09.png 2x" id="img_comp-kjcl52y9" src="https://static.wixstatic.com/media/927f01_f82687370ca84fb894c1e9440a54114c~mv2.png/v1/crop/x_0,y_170,w_856,h_856/fill/w_480,h_480,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/Screenshot%202025-03-06%20at%2016_52_09.png" alt="Screenshot 2025-03-06 at 16.52.09.png" style="width:480px;height:480px;object-fit:cover" class="BI8PVQ I5zqsT" width="480" height="480"/>
                                                                            </div>
                                                                        </div>
                                                                        <!--/$-->
                                                                        <!--$-->
                                                                        <div id="comp-kj9sumrm" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kj9sumrm wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                            <h1 class="font_0 wixui-rich-text__text" style="font-size:50px; line-height:normal;">
                                                                                <span style="font-size:50px;" class="wixui-rich-text__text">
                                                                                    <span style="letter-spacing:-0.02em;" class="wixui-rich-text__text">Dear,&nbsp;</span>
                                                                                </span>
                                                                            </h1>
                                                                        </div>
                                                                        <!--/$-->
                                                                        <!--$-->
                                                                        <div id="comp-kj9u78b4" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kj9u78b4 wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                            <p class="font_8 wixui-rich-text__text" style="line-height:1.6em; font-size:16px;">
                                                                                <span style="letter-spacing:normal;" class="wixui-rich-text__text">Here we are. You and me on a digital layer. Face to face, in different times, in different places. Check my debut novel, read it through, pay attention, drop the book and forget you even read it. Because nothing is too serious, but the tyranny of the rich, and drudgery of the dull.</span>
                                                                            </p>
                                                                        </div>
                                                                        <!--/$-->
                                                                        <!--$-->
                                                                        <div class="comp-kjcod4ll FubTgk" id="comp-kjcod4ll" aria-disabled="false">
                                                                            <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author/bio" target="_self" class="uDW_Qe wixui-button PlZyDq" aria-disabled="false">
                                                                                <span class="l7_2fn wixui-button__label">Bio</span>
                                                                            </a>
                                                                        </div>
                                                                        <!--/$-->
                                                                        <!--$-->
                                                                        <div class="comp-kjcod5ul FubTgk" id="comp-kjcod5ul" aria-disabled="false">
                                                                            <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author/projects" target="_self" class="uDW_Qe wixui-button PlZyDq" aria-disabled="false">
                                                                                <span class="l7_2fn wixui-button__label">Dear God, King David is Dead</span>
                                                                            </a>
                                                                        </div>
                                                                        <!--/$-->
                                                                        <!--$-->
                                                                        <div class="comp-kjcocqs6 FubTgk" id="comp-kjcocqs6" aria-disabled="false">
                                                                            <a data-testid="linkElement" href="https://aishtapamura.wixsite.com/author/contact" target="_self" class="uDW_Qe wixui-button PlZyDq" aria-disabled="false">
                                                                                <span class="l7_2fn wixui-button__label">Get in Touch</span>
                                                                            </a>
                                                                        </div>
                                                                        <!--/$-->
                                                                    </div>
                                                                </div>
                                                            </section>
                                                            <!--/$-->
                                                        </div>
                                                    </div>
                                                </div>
                                                <!--/$-->
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </main>
                            <!--$-->
                            <footer id="SITE_FOOTER" class="AT7o0U SITE_FOOTER wixui-footer" tabindex="-1">
                                <div class="lvxhkV"></div>
                                <div class="cKxVkc">
                                    <div class="vlM3HR"></div>
                                    <div class="VrZrC0">
                                        <div data-mesh-id="SITE_FOOTERinlineContent" data-testid="inline-content" class="">
                                            <div data-mesh-id="SITE_FOOTERinlineContent-gridContainer" data-testid="mesh-container-content">
                                                <!--$-->
                                                <div id="comp-kjcp8qvu" class="comp-kjcp8qvu aVng1S wixui-horizontal-line"></div>
                                                <!--/$-->
                                                <!--$-->
                                                <section id="comp-kj9u5y5z" class="comp-kj9u5y5z CohWsy wixui-column-strip">
                                                    <div id="bgLayers_comp-kj9u5y5z" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9u5y5z" class="if7Vw2">
                                                        <div data-testid="colorUnderlay" class="tcElKx i1tH8h"></div>
                                                        <div id="bgMedia_comp-kj9u5y5z" data-motion-part="BG_MEDIA comp-kj9u5y5z" class="wG8dni"></div>
                                                    </div>
                                                    <div data-testid="columns" class="V5AUxf">
                                                        <!--$-->
                                                        <div id="comp-kj9u5ybj" class="comp-kj9u5ybj YzqVVZ wixui-column-strip__column">
                                                            <div id="bgLayers_comp-kj9u5ybj" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9u5ybj" class="MW5IWV">
                                                                <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                <div id="bgMedia_comp-kj9u5ybj" data-motion-part="BG_MEDIA comp-kj9u5ybj" class="VgO9Yg"></div>
                                                            </div>
                                                            <div data-mesh-id="comp-kj9u5ybjinlineContent" data-testid="inline-content" class="">
                                                                <div data-mesh-id="comp-kj9u5ybjinlineContent-gridContainer" data-testid="mesh-container-content">
                                                                    <!--$-->
                                                                    <div id="comp-kjcp7mwn" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kjcp7mwn wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_5 wixui-rich-text__text" style="font-size:18px;">Phone</p>
                                                                    </div>
                                                                    <!--/$-->
                                                                    <!--$-->
                                                                    <div id="comp-kj9u7gc8" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kj9u7gc8 wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_8 wixui-rich-text__text" style="line-height:1.4em; font-size:16px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">+34 645-076-253</span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <!--/$-->
                                                        <!--$-->
                                                        <div id="comp-kj9u6b1a" class="comp-kj9u6b1a YzqVVZ wixui-column-strip__column">
                                                            <div id="bgLayers_comp-kj9u6b1a" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9u6b1a" class="MW5IWV">
                                                                <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                <div id="bgMedia_comp-kj9u6b1a" data-motion-part="BG_MEDIA comp-kj9u6b1a" class="VgO9Yg"></div>
                                                            </div>
                                                            <div data-mesh-id="comp-kj9u6b1ainlineContent" data-testid="inline-content" class="">
                                                                <div data-mesh-id="comp-kj9u6b1ainlineContent-gridContainer" data-testid="mesh-container-content">
                                                                    <!--$-->
                                                                    <div id="comp-kjcp7w67" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kjcp7w67 wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_5 wixui-rich-text__text" style="line-height:normal; font-size:18px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">Email</span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                    <!--$-->
                                                                    <div id="comp-kj9u7jfm" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kj9u7jfm wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_8 wixui-rich-text__text" style="line-height:1.4em; font-size:16px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">
                                                                                <a data-auto-recognition="true" href="mailto:aishtapamura@gmail.com" class="wixui-rich-text__text">aishtapamura@gmail.com</a>
                                                                            </span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <!--/$-->
                                                        <!--$-->
                                                        <div id="comp-kj9u6e6n" class="comp-kj9u6e6n YzqVVZ wixui-column-strip__column">
                                                            <div id="bgLayers_comp-kj9u6e6n" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kj9u6e6n" class="MW5IWV">
                                                                <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                <div id="bgMedia_comp-kj9u6e6n" data-motion-part="BG_MEDIA comp-kj9u6e6n" class="VgO9Yg"></div>
                                                            </div>
                                                            <div data-mesh-id="comp-kj9u6e6ninlineContent" data-testid="inline-content" class="">
                                                                <div data-mesh-id="comp-kj9u6e6ninlineContent-gridContainer" data-testid="mesh-container-content">
                                                                    <!--$-->
                                                                    <div id="comp-kjcp5ldh" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kjcp5ldh wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_5 wixui-rich-text__text" style="line-height:normal; font-size:18px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">Social Media</span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                    <!--$-->
                                                                    <div id="comp-kjcp46jj" class="comp-kjcp46jj WzbAF8">
                                                                        <ul class="mpGTIt" aria-label="Social Bar">
                                                                            <li id="dataItem-kjcp4sv3-comp-kjcp46jj" class="O6KwRn">
                                                                                <a data-testid="linkElement" href="https://www.linkedin.com/in/am%C3%BCre-w-anat-44b15a355/" target="_blank" rel="noreferrer noopener" class="oRtuWN" aria-label="LinkedIn">
                                                                                    <img sizes="undefinedpx" srcSet="https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_24,h_24,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/6ea5b4a88f0b4f91945b40499aa0af00.png 1x, https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_48,h_48,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/6ea5b4a88f0b4f91945b40499aa0af00.png 2x" id="img_0_comp-kjcp46jj" src="https://static.wixstatic.com/media/6ea5b4a88f0b4f91945b40499aa0af00.png/v1/fill/w_24,h_24,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/6ea5b4a88f0b4f91945b40499aa0af00.png" alt="LinkedIn" style="width:24px;height:24px;object-fit:cover" class="YaS0jR I5zqsT"/>
                                                                                </a>
                                                                            </li>
                                                                            <li id="dataItem-kjcp46po-comp-kjcp46jj" class="O6KwRn">
                                                                                <a data-testid="linkElement" href="https://www.instagram.com/renesotillo/" target="_blank" rel="noreferrer noopener" class="oRtuWN" aria-label="Instagram">
                                                                                    <img sizes="undefinedpx" srcSet="https://static.wixstatic.com/media/11062b_55e4be1e75564866b6c28290f9a9d271~mv2.png/v1/fill/w_24,h_24,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/11062b_55e4be1e75564866b6c28290f9a9d271~mv2.png 1x, https://static.wixstatic.com/media/11062b_55e4be1e75564866b6c28290f9a9d271~mv2.png/v1/fill/w_48,h_48,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/11062b_55e4be1e75564866b6c28290f9a9d271~mv2.png 2x" id="img_1_comp-kjcp46jj" src="https://static.wixstatic.com/media/11062b_55e4be1e75564866b6c28290f9a9d271~mv2.png/v1/fill/w_24,h_24,al_c,q_85,usm_0.66_1.00_0.01,enc_avif,quality_auto/11062b_55e4be1e75564866b6c28290f9a9d271~mv2.png" alt="Instagram" style="width:24px;height:24px;object-fit:cover" class="YaS0jR I5zqsT"/>
                                                                                </a>
                                                                            </li>
                                                                        </ul>
                                                                    </div>
                                                                    <!--/$-->
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <!--/$-->
                                                        <!--$-->
                                                        <div id="comp-kjcktbwb" class="comp-kjcktbwb YzqVVZ wixui-column-strip__column">
                                                            <div id="bgLayers_comp-kjcktbwb" data-hook="bgLayers" data-motion-part="BG_LAYER comp-kjcktbwb" class="MW5IWV">
                                                                <div data-testid="colorUnderlay" class="LWbAav Kv1aVt"></div>
                                                                <div id="bgMedia_comp-kjcktbwb" data-motion-part="BG_MEDIA comp-kjcktbwb" class="VgO9Yg"></div>
                                                            </div>
                                                            <div data-mesh-id="comp-kjcktbwbinlineContent" data-testid="inline-content" class="">
                                                                <div data-mesh-id="comp-kjcktbwbinlineContent-gridContainer" data-testid="mesh-container-content">
                                                                    <!--$-->
                                                                    <div id="comp-kjcktbxp" class="HcOXKn c9GqVL QxJLC3 lq2cno YQcXTT comp-kjcktbxp wixui-rich-text" data-testid="richTextElement" ariaAttributes="[object Object]">
                                                                        <p class="font_9 wixui-rich-text__text" style="line-height:1.4em; font-size:13px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">If you read this, smile. </span>
                                                                        </p>
                                                                        <p class="font_9 wixui-rich-text__text" style="line-height:1.4em; font-size:13px;">
                                                                            <span style="letter-spacing:normal;" class="wixui-rich-text__text">Or cry.</span>
                                                                        </p>
                                                                    </div>
                                                                    <!--/$-->
                                                                </div>
                                                            </div>
                                                        </div>
                                                        <!--/$-->
                                                    </div>
                                                </section>
                                                <!--/$-->
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </footer>
                            <!--/$-->
                        </div>
                        <!--/$-->
                    </div>
                    <!--$-->
                    <!--/$-->
                    <div id="SCROLL_TO_BOTTOM" class="Vd6aQZ ignore-focus SCROLL_TO_BOTTOM" tabindex="-1" role="region" aria-label="bottom of page">
                        <span class="mHZSwn">bottom of page</span>
                    </div>
                </div>
            </div>
            <script type="application/json" id="wix-fedops">
                {
                    "data": {
                        "site": {
                            "metaSiteId": "736c7394-4e87-4a3c-9265-7dad8dc29df5",
                            "userId": "927f0172-f6f8-4f97-9d48-2e8dbcef319a",
                            "siteId": "2538b395-fb67-480b-aef2-fd071e6b62dd",
                            "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                            "siteRevision": 28,
                            "siteType": "UGC",
                            "dc": "84",
                            "isResponsive": false,
                            "editorName": "Unknown",
                            "sessionId": "ffa2785f-d71b-404e-a70a-fc343b1b3785",
                            "isSEO": false,
                            "appNameForBiEvents": "thunderbolt"
                        },
                        "rollout": {
                            "siteAssetsVersionsRollout": false,
                            "isDACRollout": 0,
                            "isTBRollout": false
                        },
                        "fleetConfig": {
                            "fleetName": "wix-thunderbolt",
                            "type": "GA",
                            "code": 0
                        },
                        "requestUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                        "isInSEO": false,
                        "platformOnSite": true
                    }
                }</script>
            <script>
                window.fedops = JSON.parse(document.getElementById('wix-fedops').textContent)
            </script>
            <script id='sendFedopsLoadStarted'>
                !function() {
                    function e(e, r) {
                        var t = Object.keys(e);
                        if (Object.getOwnPropertySymbols) {
                            var n = Object.getOwnPropertySymbols(e);
                            r && (n = n.filter((function(r) {
                                return Object.getOwnPropertyDescriptor(e, r).enumerable
                            }
                            ))),
                            t.push.apply(t, n)
                        }
                        return t
                    }
                    function r(e, r, t) {
                        return (r = function(e) {
                            var r = function(e, r) {
                                if ("object" != typeof e || null === e)
                                    return e;
                                var t = e[Symbol.toPrimitive];
                                if (void 0 !== t) {
                                    var n = t.call(e, r || "default");
                                    if ("object" != typeof n)
                                        return n;
                                    throw new TypeError("@@toPrimitive must return a primitive value.")
                                }
                                return ("string" === r ? String : Number)(e)
                            }(e, "string");
                            return "symbol" == typeof r ? r : String(r)
                        }(r))in e ? Object.defineProperty(e, r, {
                            value: t,
                            enumerable: !0,
                            configurable: !0,
                            writable: !0
                        }) : e[r] = t,
                        e
                    }
                    var t = function(e) {
                        var r, t, n, o = !1;
                        if (null === (r = window.viewerModel) || void 0 === r || !/\(iP(hone|ad|od);/i.test(null === (t = window) || void 0 === t || null === (n = t.navigator) || void 0 === n ? void 0 : n.userAgent))
                            try {
                                o = navigator.sendBeacon(e)
                            } catch (e) {}
                        o || ((new Image).src = e)
                    };
                    var n = window.fedops.data
                      , o = n.site
                      , i = n.rollout
                      , a = n.fleetConfig
                      , s = n.requestUrl
                      , c = n.isInSEO
                      , shouldReportErrorOnlyInPanorama = n.shouldReportErrorOnlyInPanorama;
                    var u = function(e) {
                        var r = e.navigator.userAgent;
                        return /instagram.+google\/google/i.test(r) ? "" : /bot|google(?!play)|phantom|crawl|spider|headless|slurp|facebookexternal|Lighthouse|PTST|^mozilla\/4\.0$|^\s*$/i.test(r) ? "ua" : ""
                    }(window) || function() {
                        try {
                            if (window.self === window.top)
                                return ""
                        } catch (e) {}
                        return "iframe"
                    }() || function() {
                        var e;
                        if (!Function.prototype.bind)
                            return "bind";
                        var r = window
                          , t = r.document
                          , n = r.navigator;
                        if (!t || !n)
                            return "document";
                        var o = n.webdriver
                          , i = n.userAgent
                          , a = n.plugins
                          , s = n.languages;
                        if (o)
                            return "webdriver";
                        if (!a || Array.isArray(a))
                            return "plugins";
                        if (null !== (e = Object.getOwnPropertyDescriptor(a, "0")) && void 0 !== e && e.writable)
                            return "plugins-extra";
                        if (!i)
                            return "userAgent";
                        if (i.indexOf("Snapchat") > 0 && t.hidden)
                            return "Snapchat";
                        if (!s || 0 === s.length || !Object.isFrozen(s))
                            return "languages";
                        try {
                            throw Error()
                        } catch (e) {
                            if (e instanceof Error) {
                                var c = e.stack;
                                if (c && / (\(internal\/)|(\(?file:\/)/.test(c))
                                    return "stack"
                            }
                        }
                        return ""
                    }() || (c ? "seo" : "")
                      , l = !!u
                      , p = function(t, n) {
                        var o, i = "none", a = t.match(/ssr-caching="?cache[,#]\s*desc=([\w-]+)(?:[,#]\s*varnish=(\w+))?(?:[,#]\s*dc[,#]\s*desc=([\w-]+))?(?:"|;|$)/);
                        if (!a && window.PerformanceServerTiming) {
                            var s = function(e) {
                                var r, t;
                                try {
                                    r = e()
                                } catch (e) {
                                    r = []
                                }
                                var n = [];
                                return r.forEach((function(e) {
                                    switch (e.name) {
                                    case "cache":
                                        n[1] = e.description;
                                        break;
                                    case "varnish":
                                        n[2] = e.description;
                                        break;
                                    case "dc":
                                        t = e.description
                                    }
                                }
                                )),
                                {
                                    microPop: t,
                                    matches: n
                                }
                            }(n);
                            o = s.microPop,
                            a = s.matches
                        }
                        if (a && a.length && (i = `${a[1]},${a[2] || "none"}`,
                        o || (o = a[3])),
                        "none" === i) {
                            var c = "undefined" != typeof performance ? performance.timing : null;
                            c && c.responseStart - c.requestStart == 0 && (i = "browser")
                        }
                        return function(t) {
                            for (var n = 1; n < arguments.length; n++) {
                                var o = null != arguments[n] ? arguments[n] : {};
                                n % 2 ? e(Object(o), !0).forEach((function(e) {
                                    r(t, e, o[e])
                                }
                                )) : Object.getOwnPropertyDescriptors ? Object.defineProperties(t, Object.getOwnPropertyDescriptors(o)) : e(Object(o)).forEach((function(e) {
                                    Object.defineProperty(t, e, Object.getOwnPropertyDescriptor(o, e))
                                }
                                ))
                            }
                            return t
                        }({
                            caching: i,
                            isCached: i.includes("hit")
                        }, o ? {
                            microPop: o
                        } : {})
                    }(document.cookie, (function() {
                        return performance.getEntriesByType("navigation")[0].serverTiming || []
                    }
                    ))
                      , f = p.isCached
                      , m = p.caching
                      , v = p.microPop
                      , w = {
                        WixSite: 1,
                        UGC: 2,
                        Template: 3
                    }[o.siteType] || 0
                      , g = "Studio" === o.editorName ? "wix-studio" : o.isResponsive ? "thunderbolt-responsive" : "thunderbolt"
                      , h = i.isDACRollout
                      , b = i.siteAssetsVersionsRollout
                      , y = h ? 1 : 0
                      , x = b ? 1 : 0
                      , O = 0 === a.code || 1 === a.code ? a.code : null
                      , S = 2 === a.code
                      , P = Date.now() - window.initialTimestamps.initialTimestamp
                      , T = Math.round(performance.now())
                      , _ = document.visibilityState
                      , j = window
                      , E = j.fedops
                      , I = j.addEventListener
                      , k = j.thunderboltVersion;
                    E.apps = E.apps || {},
                    E.apps[g] = {
                        startLoadTime: T
                    },
                    E.sessionId = o.sessionId,
                    E.vsi = "xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx".replace(/[xy]/g, (function(e) {
                        var r = 16 * Math.random() | 0;
                        return ("x" === e ? r : 3 & r | 8).toString(16)
                    }
                    )),
                    E.is_cached = f,
                    E.phaseStarted = D(28),
                    E.phaseEnded = D(22),
                    performance.mark("[cache] " + m + (v ? " [" + v + "]" : "")),
                    E.reportError = function(e, r="load") {
                        var t = (null == e ? void 0 : e.reason) || (null == e ? void 0 : e.message);
                        t ? (shouldReportErrorOnlyInPanorama || R(26, `&errorInfo=${t}&errorType=${r}`),
                        $({
                            error: {
                                name: r,
                                message: t,
                                stack: e?.stack
                            }
                        })) : e.preventDefault()
                    }
                    ,
                    I("error", E.reportError),
                    I("unhandledrejection", E.reportError);
                    var A = !1;
                    function R(e) {
                        var r = arguments.length > 1 && void 0 !== arguments[1] ? arguments[1] : "";
                        if (!s.includes("suppressbi=true")) {
                            var n = "//frog.wix.com/bolt-performance?src=72&evid=" + e + "&appName=" + g + "&is_rollout=" + O + "&is_company_network=" + S + "&is_sav_rollout=" + x + "&is_dac_rollout=" + y + "&dc=" + o.dc + (v ? "&microPop=" + v : "") + "&is_cached=" + f + "&msid=" + o.metaSiteId + "&session_id=" + window.fedops.sessionId + "&ish=" + l + "&isb=" + l + (l ? "&isbr=" + u : "") + "&vsi=" + window.fedops.vsi + "&caching=" + m + (A ? ",browser_cache" : "") + "&pv=" + _ + "&pn=1&v=" + k + "&url=" + encodeURIComponent(s) + "&st=" + w + `&ts=${P}&tsn=${T}` + r;
                            t(n)
                        }
                    }
                    function $({transaction: e, error: r}) {
                        const t = [{
                            fullArtifactId: "com.wixpress.html-client.wix-thunderbolt",
                            componentId: g,
                            platform: "viewer",
                            msid: window.fedops.data.site.metaSiteId,
                            sessionId: window.fedops.sessionId,
                            sessionTime: Date.now() - window.initialTimestamps.initialTimestamp,
                            logLevel: r ? "ERROR" : "INFO",
                            message: r?.message ?? (e?.name && `${e.name} START`),
                            errorName: r?.name,
                            errorStack: r?.stack,
                            transactionName: e?.name,
                            transactionAction: e && "START",
                            isSsr: !1,
                            dataCenter: o.dc,
                            isCached: !!f,
                            isRollout: !!O,
                            isHeadless: !!l,
                            isDacRollout: !!y,
                            isSavRollout: !!x,
                            isCompanyNetwork: !!S
                        }];
                        try {
                            const e = JSON.stringify({
                                messages: t
                            });
                            return navigator.sendBeacon("https://panorama.wixapps.net/api/v1/bulklog", e)
                        } catch (e) {
                            console.error(e)
                        }
                    }
                    function D(e) {
                        return function(r, t) {
                            var n = `&name=${r}&duration=${Date.now() - P}`
                              , o = t && t.paramsOverrides ? Object.keys(t.paramsOverrides).map((function(e) {
                                return e + "=" + t.paramsOverrides[e]
                            }
                            )).join("&") : "";
                            R(e, o ? `${n}&${o}` : n)
                        }
                    }
                    I("pageshow", (function(e) {
                        e.persisted && (A || (A = !0,
                        E.is_cached = !0))
                    }
                    ), !0),
                    window.__browser_deprecation__ || (R(21, `&platformOnSite=${window.fedops.data.platformOnSite}`),
                    $({
                        transaction: {
                            name: "PANORAMA_COMPONENT_LOAD"
                        }
                    }))
                }();
            </script>
            <!-- Polyfills check -->
            <script>
                if (typeof Promise === 'undefined' || typeof Set === 'undefined' || typeof Object.assign === 'undefined' || typeof Array.from === 'undefined' || typeof Symbol === 'undefined') {
                    // send bi in order to detect the browsers in which polyfills are not working
                    window.fedops.phaseStarted('missing_polyfills')
                }
            </script>
            <!-- initCustomElements # 1-->
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/webpack-runtime.1017c466.bundle.min.js">
                ( () => {
                    "use strict";
                    var e, o, a, r, t, i = {}, n = {};
                    function d(e) {
                        var o = n[e];
                        if (void 0 !== o)
                            return o.exports;
                        var a = n[e] = {
                            id: e,
                            loaded: !1,
                            exports: {}
                        };
                        return i[e].call(a.exports, a, a.exports, d),
                        a.loaded = !0,
                        a.exports
                    }
                    d.m = i,
                    e = [],
                    d.O = (o, a, r, t) => {
                        if (!a) {
                            var i = 1 / 0;
                            for (p = 0; p < e.length; p++) {
                                for (var [a,r,t] = e[p], n = !0, s = 0; s < a.length; s++)
                                    (!1 & t || i >= t) && Object.keys(d.O).every((e => d.O[e](a[s]))) ? a.splice(s--, 1) : (n = !1,
                                    t < i && (i = t));
                                if (n) {
                                    e.splice(p--, 1);
                                    var c = r();
                                    void 0 !== c && (o = c)
                                }
                            }
                            return o
                        }
                        t = t || 0;
                        for (var p = e.length; p > 0 && e[p - 1][2] > t; p--)
                            e[p] = e[p - 1];
                        e[p] = [a, r, t]
                    }
                    ,
                    d.n = e => {
                        var o = e && e.__esModule ? () => e.default : () => e;
                        return d.d(o, {
                            a: o
                        }),
                        o
                    }
                    ,
                    a = Object.getPrototypeOf ? e => Object.getPrototypeOf(e) : e => e.__proto__,
                    d.t = function(e, r) {
                        if (1 & r && (e = this(e)),
                        8 & r)
                            return e;
                        if ("object" == typeof e && e) {
                            if (4 & r && e.__esModule)
                                return e;
                            if (16 & r && "function" == typeof e.then)
                                return e
                        }
                        var t = Object.create(null);
                        d.r(t);
                        var i = {};
                        o = o || [null, a({}), a([]), a(a)];
                        for (var n = 2 & r && e; "object" == typeof n && !~o.indexOf(n); n = a(n))
                            Object.getOwnPropertyNames(n).forEach((o => i[o] = () => e[o]));
                        return i.default = () => e,
                        d.d(t, i),
                        t
                    }
                    ,
                    d.d = (e, o) => {
                        for (var a in o)
                            d.o(o, a) && !d.o(e, a) && Object.defineProperty(e, a, {
                                enumerable: !0,
                                get: o[a]
                            })
                    }
                    ,
                    d.f = {},
                    d.e = e => Promise.all(Object.keys(d.f).reduce(( (o, a) => (d.f[a](e, o),
                    o)), [])),
                    d.u = e => 671 === e ? "thunderbolt-commons.b6b4e542.bundle.min.js" : 592 === e ? "fastdom.inline.fbeb22f8.bundle.min.js" : 996 === e ? "render-indicator.inline.44f675de.bundle.min.js" : 7122 === e ? "version-indicator.inline.5115670f.bundle.min.js" : 8398 === e ? "custom-element-utils.inline.6c144675.bundle.min.js" : ({
                        34: "FontFaces",
                        40: "wixEcomFrontendWixCodeSdk",
                        46: "TPAPopup",
                        161: "wix-seo-events-page-structured-data-index",
                        200: "wix-seo-reviews-component-index",
                        266: "group_3",
                        316: "windowScroll",
                        349: "wix-seo-breadcrumbs-component-index",
                        350: "wix-seo-static-page-v2-index",
                        359: "group_48",
                        407: "wix-seo-SEO_DEFAULT",
                        481: "wix-seo-forum-category-index",
                        541: "TPAUnavailableMessageOverlay",
                        569: "assetsLoader",
                        693: "triggersAndReactions",
                        695: "animationsWixCodeSdk",
                        711: "passwordProtectedPage",
                        740: "group_43",
                        789: "wix-seo-images-component-index",
                        851: "group_2",
                        970: "tpaWidgetNativeDeadComp",
                        974: "animations",
                        1021: "wix-seo-portfolio-collections-index",
                        1171: "platformPubsub",
                        1184: "group_18",
                        1232: "group_9",
                        1274: "ooi",
                        1305: "seo-api",
                        1494: "wix-seo-groups-post-index",
                        1499: "wix-seo-protected-page-index",
                        1501: "builderComponent",
                        1530: "wix-seo-bookings-form-index",
                        1560: "TPABaseComponent",
                        1579: "wix-seo-services-component-index",
                        1632: "SiteStyles",
                        1922: "widgetWixCodeSdk",
                        1991: "tpaModuleProvider",
                        2040: "debug",
                        2077: "wix-seo-search-page-index",
                        2177: "group_11",
                        2179: "AppPart2",
                        2305: "serviceRegistrar",
                        2313: "group_46",
                        2358: "wix-seo-blog-post-index",
                        2396: "merge-mappers",
                        2516: "presenceApi",
                        2545: "thunderbolt-components-registry",
                        2594: "tpaCommons",
                        2624: "group_21",
                        2635: "group_22",
                        2646: "platform",
                        2694: "group_38",
                        2705: "group_37",
                        2816: "wix-seo-blog-category-index",
                        2865: "Repeater_FixedColumns",
                        3002: "svgLoader",
                        3006: "wix-seo-paginated-component-index",
                        3092: "group_50",
                        3096: "wix-seo-stores-gallery-component-index",
                        3119: "Repeater_FluidColumns",
                        3272: "FontRulersContainer",
                        3286: "wix-seo-stores-product-schema-presets-index",
                        3324: "testService",
                        3495: "wix-seo-blog-tags-index",
                        3499: "wix-seo-restaurants-menu-component-index",
                        3511: "environmentWixCodeSdk",
                        3542: "dynamicPages",
                        3605: "cyclicTabbing",
                        3659: "componentsqaapi",
                        3660: "group_5",
                        3671: "group_6",
                        3682: "TPAWorker",
                        3689: "seo-api-converters",
                        3724: "versionIndicator",
                        3780: "wix-seo-schedule-page-index",
                        3795: "canvas",
                        3909: "motion",
                        3930: "mobileFullScreen",
                        3993: "group_19",
                        4047: "wix-seo-events-list-component-index",
                        4066: "TPAPreloaderOverlay",
                        4134: "group_41",
                        4206: "santa-platform-utils",
                        4245: "testApi",
                        4303: "widget",
                        4391: "wix-seo-media-component-index",
                        4456: "group_29",
                        4493: "remoteStructureRenderer",
                        4526: "group_30",
                        4551: "wix-seo-members-area-profile-tabs-index",
                        4655: "reporter-api",
                        4676: "wix-seo-events-page-index",
                        4708: "routerFetch",
                        4773: "quickActionBar",
                        4874: "wix-seo-stores-category-index",
                        5114: "wix-seo-bookings-calendar-index",
                        5116: "wix-seo-wix-data-page-item-index",
                        5122: "group_45",
                        5133: "group_42",
                        5148: "router",
                        5168: "wixDomSanitizer",
                        5219: "wix-seo-static-page-index",
                        5221: "stores",
                        5307: "wix-seo-blog-hashtags-index",
                        5377: "onloadCompsBehaviors",
                        5433: "group_20",
                        5444: "group_25",
                        5445: "protectedPages",
                        5503: "group_39",
                        5625: "group_8",
                        5648: "wix-seo-members-area-profile-index",
                        5652: "multilingual",
                        5739: "externalComponent",
                        5901: "group_51",
                        5966: "group_49",
                        5998: "stickyToComponent",
                        6055: "mpaNavigation",
                        6099: "group_35",
                        6178: "searchBox",
                        6304: "wix-seo-gift-card-index",
                        6384: "dashboardWixCodeSdk",
                        6441: "wix-seo-restaurants-menu-page-index",
                        6469: "group_4",
                        6505: "editorElementsDynamicTheme",
                        6510: "tslib.inline",
                        6521: "navigation",
                        6578: "renderIndicator",
                        6739: "presence-lazy",
                        6821: "becky-css",
                        6850: "componentsLoader",
                        6851: "wix-seo-forum-post-index",
                        6935: "module-executor",
                        6943: "group_40",
                        7030: "feedback",
                        7116: "scrollToAnchor",
                        7171: "siteMembers",
                        7230: "popups",
                        7265: "group_28",
                        7331: "RemoteRefDeadComp",
                        7393: "vsm-css",
                        7457: "group_0",
                        7471: "wix-seo-bookings-service-index",
                        7513: "wix-seo-stores-sub-category-index",
                        7547: "AppPart",
                        7562: "usedPlatformApis",
                        7882: "appMonitoring",
                        7920: "group_47",
                        7931: "group_44",
                        8039: "containerSlider",
                        8104: "tpa",
                        8149: "GhostComp",
                        8242: "group_23",
                        8253: "group_24",
                        8368: "wix-seo-programs-component-index",
                        8380: "group_14",
                        8423: "customCss",
                        8519: "qaApi",
                        8595: "wix-seo-challenges-page-index",
                        8735: "wix-seo-static-page-v2-schema-presets-index",
                        8791: "wix-seo-events-page-calculated-index",
                        8838: "group_27",
                        8840: "ByocStyles",
                        8908: "group_32",
                        8919: "group_31",
                        8934: "panorama",
                        8981: "wix-seo-groups-page-index",
                        9040: "wix-seo-restaurants-order-page-index",
                        9090: "clientSdk",
                        9098: "wix-seo-video-component-index",
                        9131: "wix-seo-payment-page-index",
                        9141: "wix-seo-pro-gallery-item-index",
                        9166: "wix-seo-portfolio-projects-index",
                        9203: "wix-seo-thank-you-page-index",
                        9278: "group_7",
                        9341: "editorWixCodeSdk",
                        9368: "group_10",
                        9506: "wix-seo-members-area-author-profile-index",
                        9507: "TPAModal",
                        9533: "wix-seo-stores-product-index",
                        9764: "wix-seo-pricing-plans-index",
                        9822: "businessManager",
                        9896: "group_36",
                        9948: "wix-seo-blog-archive-index"
                    }[e] || e) + "." + {
                        34: "b2c633d6",
                        40: "00465236",
                        46: "a513e996",
                        161: "b1d6c809",
                        198: "7c258d67",
                        200: "ee6329f6",
                        266: "82a7aa75",
                        316: "60e92730",
                        349: "16963f41",
                        350: "a043a5cc",
                        359: "9669b060",
                        407: "90df952e",
                        481: "f8e2d255",
                        490: "9be42d65",
                        516: "b0286c6f",
                        541: "19bb319e",
                        569: "1e70f802",
                        693: "e7bf7036",
                        695: "fe9dd88b",
                        711: "f6ecde33",
                        740: "238aa196",
                        789: "df97276c",
                        851: "1eaa77b9",
                        970: "264775c2",
                        974: "9ef99968",
                        1021: "cda13122",
                        1171: "482837af",
                        1184: "630297d8",
                        1232: "438c3cf0",
                        1274: "f864528d",
                        1305: "7a4a8ae6",
                        1494: "b14fc9c8",
                        1499: "d97840e9",
                        1501: "500c4a76",
                        1530: "9c7a1881",
                        1560: "cf2bf895",
                        1579: "58cae903",
                        1619: "161054ef",
                        1632: "9071ae79",
                        1922: "64a4bcd7",
                        1991: "23f9682f",
                        2040: "bab22a1a",
                        2077: "22c13f01",
                        2177: "ee0fa2c7",
                        2179: "42627332",
                        2305: "dfdac10a",
                        2313: "921f9e22",
                        2358: "09762121",
                        2396: "f017f2b0",
                        2516: "333cf8d0",
                        2545: "b89104dd",
                        2594: "59f6ed53",
                        2624: "2aad62b8",
                        2635: "d4cba985",
                        2646: "6ddf3204",
                        2694: "38642abf",
                        2705: "b4a31f0c",
                        2816: "4d2bdbc1",
                        2865: "2f69612a",
                        3002: "245384a0",
                        3006: "cf05d182",
                        3092: "5912132f",
                        3096: "5f33d809",
                        3119: "b327051f",
                        3272: "d072b975",
                        3286: "f9040bda",
                        3324: "02ec2f8b",
                        3495: "a49fe581",
                        3499: "16944fd5",
                        3511: "a8e26091",
                        3520: "0eb05960",
                        3542: "d7fc0274",
                        3605: "29f6a6d7",
                        3659: "6e9fcd51",
                        3660: "8815576b",
                        3671: "1663b443",
                        3682: "d3c73ed6",
                        3689: "284bdf94",
                        3724: "b218a6e5",
                        3780: "c52e90cd",
                        3795: "d8568ca4",
                        3909: "5309dfff",
                        3930: "5f4484e4",
                        3993: "ba72be7d",
                        4047: "c2dc0045",
                        4066: "3dedf657",
                        4134: "9290432b",
                        4206: "5fe4171d",
                        4245: "314b7383",
                        4303: "65b9a0ad",
                        4391: "f19647fe",
                        4456: "a4ae3cd3",
                        4493: "1784b28c",
                        4526: "e616afc6",
                        4551: "6afe659c",
                        4655: "6946832d",
                        4676: "120e4012",
                        4708: "9e6cb8fc",
                        4773: "95fb7bfc",
                        4874: "1344ec61",
                        5114: "63c127fe",
                        5116: "2d37ed29",
                        5122: "c635dd0f",
                        5133: "4371106b",
                        5148: "478f8b95",
                        5168: "5c048d48",
                        5219: "5c6726a5",
                        5221: "22153ee9",
                        5307: "bf11bf83",
                        5377: "a5af195f",
                        5433: "516f569a",
                        5444: "b4ae073d",
                        5445: "5c56210c",
                        5503: "e6e6b755",
                        5625: "3d51a502",
                        5648: "f27bd307",
                        5652: "08d12b42",
                        5739: "3f1960e4",
                        5901: "19163709",
                        5966: "79bde428",
                        5998: "a25627bf",
                        6055: "a33e7968",
                        6099: "7f067089",
                        6178: "814de654",
                        6304: "b1105590",
                        6384: "054adabb",
                        6441: "3aa70cad",
                        6469: "f1935415",
                        6505: "08b738a7",
                        6510: "95dc7d6c",
                        6521: "d5962942",
                        6578: "5bdd4005",
                        6739: "7fa5fd2e",
                        6821: "0f810094",
                        6850: "8acadaf2",
                        6851: "8e7881b0",
                        6935: "e59d767f",
                        6943: "f9f51e40",
                        7030: "f3c15ee1",
                        7116: "03bceb39",
                        7171: "99e7afd8",
                        7230: "9712b254",
                        7265: "a74cf8a9",
                        7331: "7984a796",
                        7393: "2d5f1321",
                        7457: "774938b3",
                        7471: "629c20d5",
                        7513: "ea74726d",
                        7547: "09b9d194",
                        7562: "7db29f51",
                        7882: "d89b6d9c",
                        7920: "4fd19472",
                        7931: "ee804dc7",
                        8039: "c4aa0c80",
                        8104: "c94318bd",
                        8149: "290fde46",
                        8242: "2bb305c8",
                        8253: "02327a7b",
                        8368: "18568241",
                        8380: "3a3ec4c6",
                        8423: "53a71ff6",
                        8519: "a501fe24",
                        8595: "e5e5b23f",
                        8735: "966f10b8",
                        8791: "c24ccaf6",
                        8838: "e86658c9",
                        8840: "73ce5462",
                        8869: "45e43a07",
                        8908: "bf2b0c3d",
                        8919: "fd9132fa",
                        8934: "2872cc39",
                        8981: "0c2dbc1e",
                        9040: "1ef6dd9e",
                        9090: "28693d5d",
                        9098: "4a07b704",
                        9131: "63e88a5f",
                        9141: "45cfa286",
                        9166: "d9d940c3",
                        9203: "5f6bebbf",
                        9278: "c50bdabd",
                        9341: "a12ad814",
                        9368: "5605f0ae",
                        9506: "54e58fa3",
                        9507: "6dfc9afe",
                        9519: "1985455d",
                        9533: "5881d4d1",
                        9622: "88c2f433",
                        9764: "d1f52483",
                        9822: "7a5cb97d",
                        9839: "a6a8764d",
                        9896: "dabdc384",
                        9948: "63464c26"
                    }[e] + ".chunk.min.js",
                    d.miniCssF = e => 996 === e ? "render-indicator.inline.044c11cb.min.css" : 7122 === e ? "version-indicator.inline.004341ff.min.css" : {
                        46: "TPAPopup",
                        541: "TPAUnavailableMessageOverlay",
                        970: "tpaWidgetNativeDeadComp",
                        1560: "TPABaseComponent",
                        2179: "AppPart2",
                        2865: "Repeater_FixedColumns",
                        3119: "Repeater_FluidColumns",
                        3272: "FontRulersContainer",
                        4066: "TPAPreloaderOverlay",
                        7547: "AppPart",
                        9278: "group_7",
                        9507: "TPAModal"
                    }[e] + "." + {
                        46: "7e7f441d",
                        541: "fb1e5320",
                        970: "edad7c2d",
                        1560: "27e1e284",
                        2179: "0a2601ec",
                        2865: "9abcda74",
                        3119: "2b7b96dd",
                        3272: "2b93f1ca",
                        4066: "6dbffa0c",
                        7547: "34a92bc1",
                        9278: "bae0ce0c",
                        9507: "52dc3d33"
                    }[e] + ".chunk.min.css",
                    d.g = function() {
                        if ("object" == typeof globalThis)
                            return globalThis;
                        try {
                            return this || new Function("return this")()
                        } catch (e) {
                            if ("object" == typeof window)
                                return window
                        }
                    }(),
                    d.o = (e, o) => Object.prototype.hasOwnProperty.call(e, o),
                    r = {},
                    t = "_wix_thunderbolt_app:",
                    d.l = (e, o, a, i) => {
                        if (r[e])
                            r[e].push(o);
                        else {
                            var n, s;
                            if (void 0 !== a)
                                for (var c = document.getElementsByTagName("script"), p = 0; p < c.length; p++) {
                                    var b = c[p];
                                    if (b.getAttribute("src") == e || b.getAttribute("data-webpack") == t + a) {
                                        n = b;
                                        break
                                    }
                                }
                            n || (s = !0,
                            (n = document.createElement("script")).charset = "utf-8",
                            n.timeout = 120,
                            d.nc && n.setAttribute("nonce", d.nc),
                            n.setAttribute("data-webpack", t + a),
                            n.src = e,
                            0 !== n.src.indexOf(window.location.origin + "/") && (n.crossOrigin = "anonymous")),
                            r[e] = [o];
                            var f = (o, a) => {
                                n.onerror = n.onload = null,
                                clearTimeout(u);
                                var t = r[e];
                                if (delete r[e],
                                n.parentNode && n.parentNode.removeChild(n),
                                t && t.forEach((e => e(a))),
                                o)
                                    return o(a)
                            }
                              , u = setTimeout(f.bind(null, void 0, {
                                type: "timeout",
                                target: n
                            }), 12e4);
                            n.onerror = f.bind(null, n.onerror),
                            n.onload = f.bind(null, n.onload),
                            s && document.head.appendChild(n)
                        }
                    }
                    ,
                    d.r = e => {
                        "undefined" != typeof Symbol && Symbol.toStringTag && Object.defineProperty(e, Symbol.toStringTag, {
                            value: "Module"
                        }),
                        Object.defineProperty(e, "__esModule", {
                            value: !0
                        })
                    }
                    ,
                    d.nmd = e => (e.paths = [],
                    e.children || (e.children = []),
                    e),
                    d.p = "https://static.parastorage.com/services/wix-thunderbolt/dist/",
                    ( () => {
                        if ("undefined" != typeof document) {
                            var e = e => new Promise(( (o, a) => {
                                var r = d.miniCssF(e)
                                  , t = d.p + r;
                                if (( (e, o) => {
                                    for (var a = document.getElementsByTagName("link"), r = 0; r < a.length; r++) {
                                        var t = (n = a[r]).getAttribute("data-href") || n.getAttribute("href");
                                        if ("stylesheet" === n.rel && (t === e || t === o))
                                            return n
                                    }
                                    var i = document.getElementsByTagName("style");
                                    for (r = 0; r < i.length; r++) {
                                        var n;
                                        if ((t = (n = i[r]).getAttribute("data-href")) === e || t === o)
                                            return n
                                    }
                                }
                                )(r, t))
                                    return o();
                                ( (e, o, a, r, t) => {
                                    var i = document.createElement("link");
                                    i.rel = "stylesheet",
                                    i.type = "text/css",
                                    i.onerror = i.onload = a => {
                                        if (i.onerror = i.onload = null,
                                        "load" === a.type)
                                            r();
                                        else {
                                            var n = a && ("load" === a.type ? "missing" : a.type)
                                              , d = a && a.target && a.target.href || o
                                              , s = new Error("Loading CSS chunk " + e + " failed.\n(" + d + ")");
                                            s.code = "CSS_CHUNK_LOAD_FAILED",
                                            s.type = n,
                                            s.request = d,
                                            i.parentNode && i.parentNode.removeChild(i),
                                            t(s)
                                        }
                                    }
                                    ,
                                    i.href = o,
                                    0 !== i.href.indexOf(window.location.origin + "/") && (i.crossOrigin = "anonymous"),
                                    a ? a.parentNode.insertBefore(i, a.nextSibling) : document.head.appendChild(i)
                                }
                                )(e, t, null, o, a)
                            }
                            ))
                              , o = {
                                7311: 0
                            };
                            d.f.miniCss = (a, r) => {
                                o[a] ? r.push(o[a]) : 0 !== o[a] && {
                                    46: 1,
                                    541: 1,
                                    970: 1,
                                    996: 1,
                                    1560: 1,
                                    2179: 1,
                                    2865: 1,
                                    3119: 1,
                                    3272: 1,
                                    4066: 1,
                                    7122: 1,
                                    7547: 1,
                                    9278: 1,
                                    9507: 1
                                }[a] && r.push(o[a] = e(a).then(( () => {
                                    o[a] = 0
                                }
                                ), (e => {
                                    throw delete o[a],
                                    e
                                }
                                )))
                            }
                        }
                    }
                    )(),
                    ( () => {
                        var e = {
                            7311: 0
                        };
                        d.f.j = (o, a) => {
                            var r = d.o(e, o) ? e[o] : void 0;
                            if (0 !== r)
                                if (r)
                                    a.push(r[2]);
                                else if (7311 != o) {
                                    var t = new Promise(( (a, t) => r = e[o] = [a, t]));
                                    a.push(r[2] = t);
                                    var i = d.p + d.u(o)
                                      , n = new Error;
                                    d.l(i, (a => {
                                        if (d.o(e, o) && (0 !== (r = e[o]) && (e[o] = void 0),
                                        r)) {
                                            var t = a && ("load" === a.type ? "missing" : a.type)
                                              , i = a && a.target && a.target.src;
                                            n.message = "Loading chunk " + o + " failed.\n(" + t + ": " + i + ")",
                                            n.name = "ChunkLoadError",
                                            n.type = t,
                                            n.request = i,
                                            r[1](n)
                                        }
                                    }
                                    ), "chunk-" + o, o)
                                } else
                                    e[o] = 0
                        }
                        ,
                        d.O.j = o => 0 === e[o];
                        var o = (o, a) => {
                            var r, t, [i,n,s] = a, c = 0;
                            if (i.some((o => 0 !== e[o]))) {
                                for (r in n)
                                    d.o(n, r) && (d.m[r] = n[r]);
                                if (s)
                                    var p = s(d)
                            }
                            for (o && o(a); c < i.length; c++)
                                t = i[c],
                                d.o(e, t) && e[t] && e[t][0](),
                                e[t] = 0;
                            return d.O(p)
                        }
                          , a = self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || [];
                        a.forEach(o.bind(null, 0)),
                        a.push = o.bind(null, a.push.bind(a))
                    }
                    )()
                }
                )();
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/webpack-runtime.1017c466.bundle.min.js.map
            </script>
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/fastdom.inline.fbeb22f8.bundle.min.js">
                (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[592], {
                    17709: function(t, e, n) {
                        var i;
                        !function(e) {
                            "use strict";
                            var r = function() {}
                              , s = e.requestAnimationFrame || e.webkitRequestAnimationFrame || e.mozRequestAnimationFrame || e.msRequestAnimationFrame || function(t) {
                                return setTimeout(t, 16)
                            }
                            ;
                            function a() {
                                var t = this;
                                t.reads = [],
                                t.writes = [],
                                t.raf = s.bind(e),
                                r("initialized", t)
                            }
                            function u(t) {
                                t.scheduled || (t.scheduled = !0,
                                t.raf(o.bind(null, t)),
                                r("flush scheduled"))
                            }
                            function o(t) {
                                r("flush");
                                var e, n = t.writes, i = t.reads;
                                try {
                                    r("flushing reads", i.length),
                                    t.runTasks(i),
                                    r("flushing writes", n.length),
                                    t.runTasks(n)
                                } catch (t) {
                                    e = t
                                }
                                if (t.scheduled = !1,
                                (i.length || n.length) && u(t),
                                e) {
                                    if (r("task errored", e.message),
                                    !t.catch)
                                        throw e;
                                    t.catch(e)
                                }
                            }
                            function c(t, e) {
                                var n = t.indexOf(e);
                                return !!~n && !!t.splice(n, 1)
                            }
                            a.prototype = {
                                constructor: a,
                                runTasks: function(t) {
                                    var e;
                                    for (r("run tasks"); e = t.shift(); )
                                        e()
                                },
                                measure: function(t, e) {
                                    r("measure");
                                    var n = e ? t.bind(e) : t;
                                    return this.reads.push(n),
                                    u(this),
                                    n
                                },
                                mutate: function(t, e) {
                                    r("mutate");
                                    var n = e ? t.bind(e) : t;
                                    return this.writes.push(n),
                                    u(this),
                                    n
                                },
                                clear: function(t) {
                                    return r("clear", t),
                                    c(this.reads, t) || c(this.writes, t)
                                },
                                extend: function(t) {
                                    if (r("extend", t),
                                    "object" != typeof t)
                                        throw new Error("expected object");
                                    var e = Object.create(this);
                                    return function(t, e) {
                                        for (var n in e)
                                            e.hasOwnProperty(n) && (t[n] = e[n])
                                    }(e, t),
                                    e.fastdom = this,
                                    e.initialize && e.initialize(),
                                    e
                                },
                                catch: null
                            };
                            var h = e.fastdom = e.fastdom || new a;
                            void 0 === (i = function() {
                                return h
                            }
                            .call(h, n, h, t)) || (t.exports = i)
                        }("undefined" != typeof window ? window : void 0 !== this ? this : globalThis)
                    }
                }]);
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/fastdom.inline.fbeb22f8.bundle.min.js.map
            </script>
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/custom-element-utils.inline.6c144675.bundle.min.js">
                "use strict";
                (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[8398], {
                    22538: (e, t, i) => {
                        i.r(t),
                        i.d(t, {
                            STATIC_MEDIA_URL: () => qe,
                            alignTypes: () => d,
                            fileType: () => v,
                            fittingTypes: () => h,
                            getData: () => $e,
                            getFileExtension: () => $,
                            getPlaceholder: () => He,
                            getResponsiveImageProps: () => Ve,
                            htmlTag: () => g,
                            isWEBP: () => G,
                            populateGlobalFeatureSupport: () => Q,
                            sdk: () => je,
                            upscaleMethods: () => p
                        });
                        const n = "v1"
                          , r = 2
                          , o = 1920
                          , s = 1920
                          , a = 1e3
                          , c = 1e3
                          , h = {
                            SCALE_TO_FILL: "fill",
                            SCALE_TO_FIT: "fit",
                            STRETCH: "stretch",
                            ORIGINAL_SIZE: "original_size",
                            TILE: "tile",
                            TILE_HORIZONTAL: "tile_horizontal",
                            TILE_VERTICAL: "tile_vertical",
                            FIT_AND_TILE: "fit_and_tile",
                            LEGACY_STRIP_TILE: "legacy_strip_tile",
                            LEGACY_STRIP_TILE_HORIZONTAL: "legacy_strip_tile_horizontal",
                            LEGACY_STRIP_TILE_VERTICAL: "legacy_strip_tile_vertical",
                            LEGACY_STRIP_SCALE_TO_FILL: "legacy_strip_fill",
                            LEGACY_STRIP_SCALE_TO_FIT: "legacy_strip_fit",
                            LEGACY_STRIP_FIT_AND_TILE: "legacy_strip_fit_and_tile",
                            LEGACY_STRIP_ORIGINAL_SIZE: "legacy_strip_original_size",
                            LEGACY_ORIGINAL_SIZE: "actual_size",
                            LEGACY_FIT_WIDTH: "fitWidth",
                            LEGACY_FIT_HEIGHT: "fitHeight",
                            LEGACY_FULL: "full",
                            LEGACY_BG_FIT_AND_TILE: "legacy_tile",
                            LEGACY_BG_FIT_AND_TILE_HORIZONTAL: "legacy_tile_horizontal",
                            LEGACY_BG_FIT_AND_TILE_VERTICAL: "legacy_tile_vertical",
                            LEGACY_BG_NORMAL: "legacy_normal"
                        }
                          , l = {
                            FIT: "fit",
                            FILL: "fill",
                            FILL_FOCAL: "fill_focal",
                            CROP: "crop",
                            LEGACY_CROP: "legacy_crop",
                            LEGACY_FILL: "legacy_fill"
                        }
                          , d = {
                            CENTER: "center",
                            TOP: "top",
                            TOP_LEFT: "top_left",
                            TOP_RIGHT: "top_right",
                            BOTTOM: "bottom",
                            BOTTOM_LEFT: "bottom_left",
                            BOTTOM_RIGHT: "bottom_right",
                            LEFT: "left",
                            RIGHT: "right"
                        }
                          , u = {
                            [d.CENTER]: {
                                x: .5,
                                y: .5
                            },
                            [d.TOP_LEFT]: {
                                x: 0,
                                y: 0
                            },
                            [d.TOP_RIGHT]: {
                                x: 1,
                                y: 0
                            },
                            [d.TOP]: {
                                x: .5,
                                y: 0
                            },
                            [d.BOTTOM_LEFT]: {
                                x: 0,
                                y: 1
                            },
                            [d.BOTTOM_RIGHT]: {
                                x: 1,
                                y: 1
                            },
                            [d.BOTTOM]: {
                                x: .5,
                                y: 1
                            },
                            [d.RIGHT]: {
                                x: 1,
                                y: .5
                            },
                            [d.LEFT]: {
                                x: 0,
                                y: .5
                            }
                        }
                          , m = {
                            center: "c",
                            top: "t",
                            top_left: "tl",
                            top_right: "tr",
                            bottom: "b",
                            bottom_left: "bl",
                            bottom_right: "br",
                            left: "l",
                            right: "r"
                        }
                          , g = {
                            BG: "bg",
                            IMG: "img",
                            SVG: "svg"
                        }
                          , p = {
                            AUTO: "auto",
                            CLASSIC: "classic",
                            SUPER: "super"
                        }
                          , f = {
                            classic: 1,
                            super: 2
                        }
                          , b = {
                            radius: "0.66",
                            amount: "1.00",
                            threshold: "0.01"
                        }
                          , _ = {
                            uri: "",
                            css: {
                                img: {},
                                container: {}
                            },
                            attr: {
                                img: {},
                                container: {}
                            },
                            transformed: !1
                        }
                          , T = 25e6
                          , I = [1.5, 2, 4]
                          , E = {
                            HIGH: {
                                size: 196e4,
                                quality: 90,
                                maxUpscale: 1
                            },
                            MEDIUM: {
                                size: 36e4,
                                quality: 85,
                                maxUpscale: 1
                            },
                            LOW: {
                                size: 16e4,
                                quality: 80,
                                maxUpscale: 1.2
                            },
                            TINY: {
                                size: 0,
                                quality: 80,
                                maxUpscale: 1.4
                            }
                        }
                          , L = {
                            HIGH: "HIGH",
                            MEDIUM: "MEDIUM",
                            LOW: "LOW",
                            TINY: "TINY"
                        }
                          , w = {
                            CONTRAST: "contrast",
                            BRIGHTNESS: "brightness",
                            SATURATION: "saturation",
                            HUE: "hue",
                            BLUR: "blur"
                        }
                          , v = {
                            JPG: "jpg",
                            JPEG: "jpeg",
                            JPE: "jpe",
                            PNG: "png",
                            WEBP: "webp",
                            WIX_ICO_MP: "wix_ico_mp",
                            WIX_MP: "wix_mp",
                            GIF: "gif",
                            SVG: "svg",
                            AVIF: "avif",
                            UNRECOGNIZED: "unrecognized"
                        }
                          , A = {
                            AVIF: "AVIF",
                            PAVIF: "PAVIF"
                        };
                        v.JPG,
                        v.JPEG,
                        v.JPE,
                        v.PNG,
                        v.GIF,
                        v.WEBP;
                        function O(e, ...t) {
                            return function(...i) {
                                const n = i[i.length - 1] || {}
                                  , r = [e[0]];
                                return t.forEach((function(t, o) {
                                    const s = Number.isInteger(t) ? i[t] : n[t];
                                    r.push(s, e[o + 1])
                                }
                                )),
                                r.join("")
                            }
                        }
                        function C(e) {
                            return e[e.length - 1]
                        }
                        const R = [v.PNG, v.JPEG, v.JPG, v.JPE, v.WIX_ICO_MP, v.WIX_MP, v.WEBP, v.AVIF]
                          , y = [v.JPEG, v.JPG, v.JPE];
                        function M(e, t, i) {
                            return i && t && !(!(n = t.id) || !n.trim() || "none" === n.toLowerCase()) && Object.values(h).includes(e);
                            var n
                        }
                        function S(e, t, i) {
                            return function(e, t, i=!1) {
                                return !((G(e) || N(e)) && t && !i)
                            }(e, t, i) && (function(e) {
                                return R.includes($(e))
                            }(e) || function(e, t=!1) {
                                return F(e) && t
                            }(e, i)) && !/(^https?)|(^data)|(^\/\/)/.test(e)
                        }
                        function x(e) {
                            return $(e) === v.PNG
                        }
                        function G(e) {
                            return $(e) === v.WEBP
                        }
                        function F(e) {
                            return $(e) === v.GIF
                        }
                        function N(e) {
                            return $(e) === v.AVIF
                        }
                        const P = ["/", "\\", "?", "<", ">", "|", "\u201c", ":", '"'].map(encodeURIComponent)
                          , k = ["\\.", "\\*"]
                          , B = "_";
                        function H(e) {
                            return function(e) {
                                return y.includes($(e))
                            }(e) ? v.JPG : x(e) ? v.PNG : G(e) ? v.WEBP : F(e) ? v.GIF : N(e) ? v.AVIF : v.UNRECOGNIZED
                        }
                        function $(e) {
                            return (/[.]([^.]+)$/.exec(e) && /[.]([^.]+)$/.exec(e)[1] || "").toLowerCase()
                        }
                        function U(e, t, i, n, r) {
                            let o;
                            return o = r === l.FILL ? function(e, t, i, n) {
                                return Math.max(i / e, n / t)
                            }(e, t, i, n) : r === l.FIT ? function(e, t, i, n) {
                                return Math.min(i / e, n / t)
                            }(e, t, i, n) : 1,
                            o
                        }
                        function W(e, t, i, n, r, o) {
                            e = e || n.width,
                            t = t || n.height;
                            const {scaleFactor: s, width: a, height: c} = function(e, t, i, n, r) {
                                let o, s = i, a = n;
                                if (o = U(e, t, i, n, r),
                                r === l.FIT && (s = e * o,
                                a = t * o),
                                s && a && s * a > T) {
                                    const i = Math.sqrt(T / (s * a));
                                    s *= i,
                                    a *= i,
                                    o = U(e, t, s, a, r)
                                }
                                return {
                                    scaleFactor: o,
                                    width: s,
                                    height: a
                                }
                            }(e, t, n.width * r, n.height * r, i);
                            return function(e, t, i, n, r, o, s) {
                                const {optimizedScaleFactor: a, upscaleMethodValue: c, forceUSM: h} = function(e, t, i, n) {
                                    if ("auto" === n)
                                        return function(e, t) {
                                            const i = V(e, t);
                                            return {
                                                optimizedScaleFactor: E[i].maxUpscale,
                                                upscaleMethodValue: f.classic,
                                                forceUSM: !1
                                            }
                                        }(e, t);
                                    if ("super" === n)
                                        return function(e) {
                                            return {
                                                optimizedScaleFactor: C(I),
                                                upscaleMethodValue: f.super,
                                                forceUSM: !(I.includes(e) || e > C(I))
                                            }
                                        }(i);
                                    return function(e, t) {
                                        const i = V(e, t);
                                        return {
                                            optimizedScaleFactor: E[i].maxUpscale,
                                            upscaleMethodValue: f.classic,
                                            forceUSM: !1
                                        }
                                    }(e, t)
                                }(e, t, o, r);
                                let d = i
                                  , u = n;
                                if (o <= a)
                                    return {
                                        width: d,
                                        height: u,
                                        scaleFactor: o,
                                        upscaleMethodValue: c,
                                        forceUSM: h,
                                        cssUpscaleNeeded: !1
                                    };
                                switch (s) {
                                case l.FILL:
                                    d = i * (a / o),
                                    u = n * (a / o);
                                    break;
                                case l.FIT:
                                    d = e * a,
                                    u = t * a
                                }
                                return {
                                    width: d,
                                    height: u,
                                    scaleFactor: a,
                                    upscaleMethodValue: c,
                                    forceUSM: h,
                                    cssUpscaleNeeded: !0
                                }
                            }(e, t, a, c, o, s, i)
                        }
                        function z(e, t, i, n) {
                            const r = D(i) || function(e=d.CENTER) {
                                return u[e]
                            }(n);
                            return {
                                x: Math.max(0, Math.min(e.width - t.width, r.x * e.width - t.width / 2)),
                                y: Math.max(0, Math.min(e.height - t.height, r.y * e.height - t.height / 2)),
                                width: Math.min(e.width, t.width),
                                height: Math.min(e.height, t.height)
                            }
                        }
                        function Y(e) {
                            return e.alignment && m[e.alignment] || m[d.CENTER]
                        }
                        function D(e) {
                            let t;
                            return !e || "number" != typeof e.x || isNaN(e.x) || "number" != typeof e.y || isNaN(e.y) || (t = {
                                x: j(Math.max(0, Math.min(100, e.x)) / 100, 2),
                                y: j(Math.max(0, Math.min(100, e.y)) / 100, 2)
                            }),
                            t
                        }
                        function V(e, t) {
                            const i = e * t;
                            return i > E[L.HIGH].size ? L.HIGH : i > E[L.MEDIUM].size ? L.MEDIUM : i > E[L.LOW].size ? L.LOW : L.TINY
                        }
                        function j(e, t) {
                            const i = Math.pow(10, t || 0);
                            return (e * i / i).toFixed(t)
                        }
                        function q(e) {
                            return e && e.upscaleMethod && p[e.upscaleMethod.toUpperCase()] || p.AUTO
                        }
                        function Z(e, t) {
                            const i = G(e) || N(e);
                            return $(e) === v.GIF || i && t
                        }
                        const J = {
                            isMobile: !1
                        }
                          , X = function(e) {
                            return J[e]
                        }
                          , K = function(e, t) {
                            J[e] = t
                        };
                        function Q() {
                            if ("undefined" != typeof window && "undefined" != typeof navigator) {
                                const e = window.matchMedia && window.matchMedia("(max-width: 767px)").matches
                                  , t = /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent);
                                K("isMobile", e && t)
                            }
                        }
                        function ee(e, t) {
                            const i = {
                                css: {
                                    container: {}
                                }
                            }
                              , {css: n} = i
                              , {fittingType: r} = e;
                            switch (r) {
                            case h.ORIGINAL_SIZE:
                            case h.LEGACY_ORIGINAL_SIZE:
                            case h.LEGACY_STRIP_ORIGINAL_SIZE:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "no-repeat";
                                break;
                            case h.SCALE_TO_FIT:
                            case h.LEGACY_STRIP_SCALE_TO_FIT:
                                n.container.backgroundSize = "contain",
                                n.container.backgroundRepeat = "no-repeat";
                                break;
                            case h.STRETCH:
                                n.container.backgroundSize = "100% 100%",
                                n.container.backgroundRepeat = "no-repeat";
                                break;
                            case h.SCALE_TO_FILL:
                            case h.LEGACY_STRIP_SCALE_TO_FILL:
                                n.container.backgroundSize = "cover",
                                n.container.backgroundRepeat = "no-repeat";
                                break;
                            case h.TILE_HORIZONTAL:
                            case h.LEGACY_STRIP_TILE_HORIZONTAL:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "repeat-x";
                                break;
                            case h.TILE_VERTICAL:
                            case h.LEGACY_STRIP_TILE_VERTICAL:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "repeat-y";
                                break;
                            case h.TILE:
                            case h.LEGACY_STRIP_TILE:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "repeat";
                                break;
                            case h.LEGACY_STRIP_FIT_AND_TILE:
                                n.container.backgroundSize = "contain",
                                n.container.backgroundRepeat = "repeat";
                                break;
                            case h.FIT_AND_TILE:
                            case h.LEGACY_BG_FIT_AND_TILE:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "repeat";
                                break;
                            case h.LEGACY_BG_FIT_AND_TILE_HORIZONTAL:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "repeat-x";
                                break;
                            case h.LEGACY_BG_FIT_AND_TILE_VERTICAL:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "repeat-y";
                                break;
                            case h.LEGACY_BG_NORMAL:
                                n.container.backgroundSize = "auto",
                                n.container.backgroundRepeat = "no-repeat"
                            }
                            switch (t.alignment) {
                            case d.CENTER:
                                n.container.backgroundPosition = "center center";
                                break;
                            case d.LEFT:
                                n.container.backgroundPosition = "left center";
                                break;
                            case d.RIGHT:
                                n.container.backgroundPosition = "right center";
                                break;
                            case d.TOP:
                                n.container.backgroundPosition = "center top";
                                break;
                            case d.BOTTOM:
                                n.container.backgroundPosition = "center bottom";
                                break;
                            case d.TOP_RIGHT:
                                n.container.backgroundPosition = "right top";
                                break;
                            case d.TOP_LEFT:
                                n.container.backgroundPosition = "left top";
                                break;
                            case d.BOTTOM_RIGHT:
                                n.container.backgroundPosition = "right bottom";
                                break;
                            case d.BOTTOM_LEFT:
                                n.container.backgroundPosition = "left bottom"
                            }
                            return i
                        }
                        const te = {
                            [d.CENTER]: "center",
                            [d.TOP]: "top",
                            [d.TOP_LEFT]: "top left",
                            [d.TOP_RIGHT]: "top right",
                            [d.BOTTOM]: "bottom",
                            [d.BOTTOM_LEFT]: "bottom left",
                            [d.BOTTOM_RIGHT]: "bottom right",
                            [d.LEFT]: "left",
                            [d.RIGHT]: "right"
                        }
                          , ie = {
                            position: "absolute",
                            top: "auto",
                            right: "auto",
                            bottom: "auto",
                            left: "auto"
                        };
                        function ne(e, t) {
                            const i = {
                                css: {
                                    container: {},
                                    img: {}
                                }
                            }
                              , {css: n} = i
                              , {fittingType: r} = e
                              , o = t.alignment;
                            switch (n.container.position = "relative",
                            r) {
                            case h.ORIGINAL_SIZE:
                            case h.LEGACY_ORIGINAL_SIZE:
                                e.parts && e.parts.length ? (n.img.width = e.parts[0].width,
                                n.img.height = e.parts[0].height) : (n.img.width = e.src.width,
                                n.img.height = e.src.height);
                                break;
                            case h.SCALE_TO_FIT:
                            case h.LEGACY_FIT_WIDTH:
                            case h.LEGACY_FIT_HEIGHT:
                            case h.LEGACY_FULL:
                                n.img.width = t.width,
                                n.img.height = t.height,
                                n.img.objectFit = "contain",
                                n.img.objectPosition = te[o] || "unset";
                                break;
                            case h.LEGACY_BG_NORMAL:
                                n.img.width = "100%",
                                n.img.height = "100%",
                                n.img.objectFit = "none",
                                n.img.objectPosition = te[o] || "unset";
                                break;
                            case h.STRETCH:
                                n.img.width = t.width,
                                n.img.height = t.height,
                                n.img.objectFit = "fill";
                                break;
                            case h.SCALE_TO_FILL:
                                n.img.width = t.width,
                                n.img.height = t.height,
                                n.img.objectFit = "cover"
                            }
                            if ("number" == typeof n.img.width && "number" == typeof n.img.height && (n.img.width !== t.width || n.img.height !== t.height)) {
                                const e = Math.round((t.height - n.img.height) / 2)
                                  , i = Math.round((t.width - n.img.width) / 2);
                                Object.assign(n.img, ie, function(e, t, i) {
                                    return {
                                        [d.TOP_LEFT]: {
                                            top: 0,
                                            left: 0
                                        },
                                        [d.TOP_RIGHT]: {
                                            top: 0,
                                            right: 0
                                        },
                                        [d.TOP]: {
                                            top: 0,
                                            left: t
                                        },
                                        [d.BOTTOM_LEFT]: {
                                            bottom: 0,
                                            left: 0
                                        },
                                        [d.BOTTOM_RIGHT]: {
                                            bottom: 0,
                                            right: 0
                                        },
                                        [d.BOTTOM]: {
                                            bottom: 0,
                                            left: t
                                        },
                                        [d.RIGHT]: {
                                            top: e,
                                            right: 0
                                        },
                                        [d.LEFT]: {
                                            top: e,
                                            left: 0
                                        },
                                        [d.CENTER]: {
                                            width: i.width,
                                            height: i.height,
                                            objectFit: "none"
                                        }
                                    }
                                }(e, i, t)[o])
                            }
                            return i
                        }
                        function re(e, t) {
                            const i = {
                                css: {
                                    container: {}
                                },
                                attr: {
                                    container: {},
                                    img: {}
                                }
                            }
                              , {css: n, attr: r} = i
                              , {fittingType: o} = e
                              , s = t.alignment
                              , {width: a, height: c} = e.src;
                            let u;
                            switch (n.container.position = "relative",
                            o) {
                            case h.ORIGINAL_SIZE:
                            case h.LEGACY_ORIGINAL_SIZE:
                            case h.TILE:
                                e.parts && e.parts.length ? (r.img.width = e.parts[0].width,
                                r.img.height = e.parts[0].height) : (r.img.width = a,
                                r.img.height = c),
                                r.img.preserveAspectRatio = "xMidYMid slice";
                                break;
                            case h.SCALE_TO_FIT:
                            case h.LEGACY_FIT_WIDTH:
                            case h.LEGACY_FIT_HEIGHT:
                            case h.LEGACY_FULL:
                                r.img.width = "100%",
                                r.img.height = "100%",
                                r.img.transform = "",
                                r.img.preserveAspectRatio = "";
                                break;
                            case h.STRETCH:
                                r.img.width = t.width,
                                r.img.height = t.height,
                                r.img.x = 0,
                                r.img.y = 0,
                                r.img.transform = "",
                                r.img.preserveAspectRatio = "none";
                                break;
                            case h.SCALE_TO_FILL:
                                S(e.src.id) ? (r.img.width = t.width,
                                r.img.height = t.height) : (u = function(e, t, i, n, r) {
                                    const o = U(e, t, i, n, r);
                                    return {
                                        width: Math.round(e * o),
                                        height: Math.round(t * o)
                                    }
                                }(a, c, t.width, t.height, l.FILL),
                                r.img.width = u.width,
                                r.img.height = u.height),
                                r.img.x = 0,
                                r.img.y = 0,
                                r.img.transform = "",
                                r.img.preserveAspectRatio = "xMidYMid slice"
                            }
                            if ("number" == typeof r.img.width && "number" == typeof r.img.height && (r.img.width !== t.width || r.img.height !== t.height)) {
                                let e, i, n = 0, a = 0;
                                o === h.TILE ? (e = t.width % r.img.width,
                                i = t.height % r.img.height) : (e = t.width - r.img.width,
                                i = t.height - r.img.height);
                                const c = Math.round(e / 2)
                                  , l = Math.round(i / 2);
                                switch (s) {
                                case d.TOP_LEFT:
                                    n = 0,
                                    a = 0;
                                    break;
                                case d.TOP:
                                    n = c,
                                    a = 0;
                                    break;
                                case d.TOP_RIGHT:
                                    n = e,
                                    a = 0;
                                    break;
                                case d.LEFT:
                                    n = 0,
                                    a = l;
                                    break;
                                case d.CENTER:
                                    n = c,
                                    a = l;
                                    break;
                                case d.RIGHT:
                                    n = e,
                                    a = l;
                                    break;
                                case d.BOTTOM_LEFT:
                                    n = 0,
                                    a = i;
                                    break;
                                case d.BOTTOM:
                                    n = c,
                                    a = i;
                                    break;
                                case d.BOTTOM_RIGHT:
                                    n = e,
                                    a = i
                                }
                                r.img.x = n,
                                r.img.y = a
                            }
                            return r.container.width = t.width,
                            r.container.height = t.height,
                            r.container.viewBox = [0, 0, t.width, t.height].join(" "),
                            i
                        }
                        function oe(e, t, i) {
                            let n;
                            switch (t.crop && (n = function(e, t) {
                                const i = Math.max(0, Math.min(e.width, t.x + t.width) - Math.max(0, t.x))
                                  , n = Math.max(0, Math.min(e.height, t.y + t.height) - Math.max(0, t.y));
                                return i && n && (e.width !== i || e.height !== n) ? {
                                    x: Math.max(0, t.x),
                                    y: Math.max(0, t.y),
                                    width: i,
                                    height: n
                                } : null
                            }(t, t.crop),
                            n && (e.src.width = n.width,
                            e.src.height = n.height,
                            e.src.isCropped = !0,
                            e.parts.push(ae(n)))),
                            e.fittingType) {
                            case h.SCALE_TO_FIT:
                            case h.LEGACY_FIT_WIDTH:
                            case h.LEGACY_FIT_HEIGHT:
                            case h.LEGACY_FULL:
                            case h.FIT_AND_TILE:
                            case h.LEGACY_BG_FIT_AND_TILE:
                            case h.LEGACY_BG_FIT_AND_TILE_HORIZONTAL:
                            case h.LEGACY_BG_FIT_AND_TILE_VERTICAL:
                            case h.LEGACY_BG_NORMAL:
                                e.parts.push(se(e, i));
                                break;
                            case h.SCALE_TO_FILL:
                                e.parts.push(function(e, t) {
                                    const i = W(e.src.width, e.src.height, l.FILL, t, e.devicePixelRatio, e.upscaleMethod)
                                      , n = D(e.focalPoint);
                                    return {
                                        transformType: n ? l.FILL_FOCAL : l.FILL,
                                        width: Math.round(i.width),
                                        height: Math.round(i.height),
                                        alignment: Y(t),
                                        focalPointX: n && n.x,
                                        focalPointY: n && n.y,
                                        upscale: i.scaleFactor > 1,
                                        forceUSM: i.forceUSM,
                                        scaleFactor: i.scaleFactor,
                                        cssUpscaleNeeded: i.cssUpscaleNeeded,
                                        upscaleMethodValue: i.upscaleMethodValue
                                    }
                                }(e, i));
                                break;
                            case h.STRETCH:
                                e.parts.push(function(e, t) {
                                    const i = U(e.src.width, e.src.height, t.width, t.height, l.FILL)
                                      , n = {
                                        ...t
                                    };
                                    return n.width = e.src.width * i,
                                    n.height = e.src.height * i,
                                    se(e, n)
                                }(e, i));
                                break;
                            case h.TILE_HORIZONTAL:
                            case h.TILE_VERTICAL:
                            case h.TILE:
                            case h.LEGACY_ORIGINAL_SIZE:
                            case h.ORIGINAL_SIZE:
                                n = z(e.src, i, e.focalPoint, i.alignment),
                                e.src.isCropped ? (Object.assign(e.parts[0], n),
                                e.src.width = n.width,
                                e.src.height = n.height) : e.parts.push(ae(n));
                                break;
                            case h.LEGACY_STRIP_TILE_HORIZONTAL:
                            case h.LEGACY_STRIP_TILE_VERTICAL:
                            case h.LEGACY_STRIP_TILE:
                            case h.LEGACY_STRIP_ORIGINAL_SIZE:
                                e.parts.push(function(e) {
                                    return {
                                        transformType: l.LEGACY_CROP,
                                        width: Math.round(e.width),
                                        height: Math.round(e.height),
                                        alignment: Y(e),
                                        upscale: !1,
                                        forceUSM: !1,
                                        scaleFactor: 1,
                                        cssUpscaleNeeded: !1
                                    }
                                }(i));
                                break;
                            case h.LEGACY_STRIP_SCALE_TO_FIT:
                            case h.LEGACY_STRIP_FIT_AND_TILE:
                                e.parts.push(function(e) {
                                    return {
                                        transformType: l.FIT,
                                        width: Math.round(e.width),
                                        height: Math.round(e.height),
                                        upscale: !1,
                                        forceUSM: !0,
                                        scaleFactor: 1,
                                        cssUpscaleNeeded: !1
                                    }
                                }(i));
                                break;
                            case h.LEGACY_STRIP_SCALE_TO_FILL:
                                e.parts.push(function(e) {
                                    return {
                                        transformType: l.LEGACY_FILL,
                                        width: Math.round(e.width),
                                        height: Math.round(e.height),
                                        alignment: Y(e),
                                        upscale: !1,
                                        forceUSM: !0,
                                        scaleFactor: 1,
                                        cssUpscaleNeeded: !1
                                    }
                                }(i))
                            }
                        }
                        function se(e, t) {
                            const i = W(e.src.width, e.src.height, l.FIT, t, e.devicePixelRatio, e.upscaleMethod);
                            return {
                                transformType: !e.src.width || !e.src.height ? l.FIT : l.FILL,
                                width: Math.round(i.width),
                                height: Math.round(i.height),
                                alignment: m.center,
                                upscale: i.scaleFactor > 1,
                                forceUSM: i.forceUSM,
                                scaleFactor: i.scaleFactor,
                                cssUpscaleNeeded: i.cssUpscaleNeeded,
                                upscaleMethodValue: i.upscaleMethodValue
                            }
                        }
                        function ae(e) {
                            return {
                                transformType: l.CROP,
                                x: Math.round(e.x),
                                y: Math.round(e.y),
                                width: Math.round(e.width),
                                height: Math.round(e.height),
                                upscale: !1,
                                forceUSM: !1,
                                scaleFactor: 1,
                                cssUpscaleNeeded: !1
                            }
                        }
                        function ce(e, t) {
                            t = t || {},
                            e.quality = function(e, t) {
                                const i = e.fileType === v.PNG
                                  , n = e.fileType === v.JPG
                                  , r = e.fileType === v.WEBP
                                  , o = e.fileType === v.AVIF
                                  , s = n || i || r || o;
                                if (s) {
                                    const n = C(e.parts)
                                      , r = (a = n.width,
                                    c = n.height,
                                    E[V(a, c)].quality);
                                    let o = t.quality && t.quality >= 5 && t.quality <= 90 ? t.quality : r;
                                    return o = i ? o + 5 : o,
                                    o
                                }
                                var a, c;
                                return 0
                            }(e, t),
                            e.progressive = function(e) {
                                return !1 !== e.progressive
                            }(t),
                            e.watermark = function(e) {
                                return e.watermark
                            }(t),
                            e.autoEncode = t.autoEncode ?? !0,
                            e.encoding = t?.encoding,
                            e.unsharpMask = function(e, t) {
                                if (function(e) {
                                    const t = "number" == typeof (e = e || {}).radius && !isNaN(e.radius) && e.radius >= .1 && e.radius <= 500
                                      , i = "number" == typeof e.amount && !isNaN(e.amount) && e.amount >= 0 && e.amount <= 10
                                      , n = "number" == typeof e.threshold && !isNaN(e.threshold) && e.threshold >= 0 && e.threshold <= 255;
                                    return t && i && n
                                }(t.unsharpMask))
                                    return {
                                        radius: j(t.unsharpMask?.radius, 2),
                                        amount: j(t.unsharpMask?.amount, 2),
                                        threshold: j(t.unsharpMask?.threshold, 2)
                                    };
                                if (("number" != typeof (i = (i = t.unsharpMask) || {}).radius || isNaN(i.radius) || 0 !== i.radius || "number" != typeof i.amount || isNaN(i.amount) || 0 !== i.amount || "number" != typeof i.threshold || isNaN(i.threshold) || 0 !== i.threshold) && function(e) {
                                    const t = C(e.parts);
                                    return !(t.scaleFactor >= 1) || t.forceUSM || t.transformType === l.FIT
                                }(e))
                                    return b;
                                var i;
                                return
                            }(e, t),
                            e.filters = function(e) {
                                const t = e.filters || {}
                                  , i = {};
                                he(t[w.CONTRAST], -100, 100) && (i[w.CONTRAST] = t[w.CONTRAST]);
                                he(t[w.BRIGHTNESS], -100, 100) && (i[w.BRIGHTNESS] = t[w.BRIGHTNESS]);
                                he(t[w.SATURATION], -100, 100) && (i[w.SATURATION] = t[w.SATURATION]);
                                he(t[w.HUE], -180, 180) && (i[w.HUE] = t[w.HUE]);
                                he(t[w.BLUR], 0, 100) && (i[w.BLUR] = t[w.BLUR]);
                                return i
                            }(t)
                        }
                        function he(e, t, i) {
                            return "number" == typeof e && !isNaN(e) && 0 !== e && e >= t && e <= i
                        }
                        function le(e, t, i, n) {
                            const o = function(e) {
                                return e?.isSEOBot ?? !1
                            }(n)
                              , s = H(t.id)
                              , a = function(e, t) {
                                const i = /\.([^.]*)$/
                                  , n = new RegExp(`(${P.concat(k).join("|")})`,"g");
                                if (t && t.length) {
                                    let e = t;
                                    const r = t.match(i);
                                    return r && R.includes(r[1]) && (e = t.replace(i, "")),
                                    encodeURIComponent(e).replace(n, B)
                                }
                                const r = e.match(/\/(.*?)$/);
                                return (r ? r[1] : e).replace(i, "")
                            }(t.id, t.name)
                              , c = o ? 1 : function(e) {
                                return Math.min(e.pixelAspectRatio || 1, r)
                            }(i)
                              , h = $(t.id)
                              , l = h
                              , d = S(t.id, n?.hasAnimation, n?.allowAnimatedTransform)
                              , u = {
                                fileName: a,
                                fileExtension: h,
                                fileType: s,
                                fittingType: e,
                                preferredExtension: l,
                                src: {
                                    id: t.id,
                                    width: t.width,
                                    height: t.height,
                                    isCropped: !1,
                                    isAnimated: Z(t.id, n?.hasAnimation)
                                },
                                focalPoint: {
                                    x: t.focalPoint && t.focalPoint.x,
                                    y: t.focalPoint && t.focalPoint.y
                                },
                                parts: [],
                                devicePixelRatio: c,
                                quality: 0,
                                upscaleMethod: q(n),
                                progressive: !0,
                                watermark: "",
                                unsharpMask: {},
                                filters: {},
                                transformed: d
                            };
                            return d && (oe(u, t, i),
                            ce(u, n)),
                            u
                        }
                        function de(e, t, i) {
                            const n = {
                                ...i
                            }
                              , r = X("isMobile");
                            switch (e) {
                            case h.LEGACY_BG_FIT_AND_TILE:
                            case h.LEGACY_BG_FIT_AND_TILE_HORIZONTAL:
                            case h.LEGACY_BG_FIT_AND_TILE_VERTICAL:
                            case h.LEGACY_BG_NORMAL:
                                const e = r ? a : o
                                  , i = r ? c : s;
                                n.width = Math.min(e, t.width),
                                n.height = Math.min(i, Math.round(n.width / (t.width / t.height))),
                                n.pixelAspectRatio = 1
                            }
                            return n
                        }
                        const ue = O`fit/w_${"width"},h_${"height"}`
                          , me = O`fill/w_${"width"},h_${"height"},al_${"alignment"}`
                          , ge = O`fill/w_${"width"},h_${"height"},fp_${"focalPointX"}_${"focalPointY"}`
                          , pe = O`crop/x_${"x"},y_${"y"},w_${"width"},h_${"height"}`
                          , fe = O`crop/w_${"width"},h_${"height"},al_${"alignment"}`
                          , be = O`fill/w_${"width"},h_${"height"},al_${"alignment"}`
                          , _e = O`,lg_${"upscaleMethodValue"}`
                          , Te = O`,q_${"quality"}`
                          , Ie = O`,quality_auto`
                          , Ee = O`,usm_${"radius"}_${"amount"}_${"threshold"}`
                          , Le = O`,bl`
                          , we = O`,wm_${"watermark"}`
                          , ve = {
                            [w.CONTRAST]: O`,con_${"contrast"}`,
                            [w.BRIGHTNESS]: O`,br_${"brightness"}`,
                            [w.SATURATION]: O`,sat_${"saturation"}`,
                            [w.HUE]: O`,hue_${"hue"}`,
                            [w.BLUR]: O`,blur_${"blur"}`
                        }
                          , Ae = O`,enc_auto`
                          , Oe = O`,enc_avif`
                          , Ce = O`,enc_pavif`
                          , Re = O`,pstr`;
                        function ye(e, t, i, r={}, o) {
                            if (S(t.id, r?.hasAnimation, r?.allowAnimatedTransform)) {
                                if (G(t.id) || N(t.id)) {
                                    const {alignment: n, ...s} = i;
                                    t.focalPoint = {
                                        x: void 0,
                                        y: void 0
                                    },
                                    delete t?.crop,
                                    o = le(e, t, s, r)
                                } else
                                    o = o || le(e, t, i, r);
                                return function(e) {
                                    const t = [];
                                    e.parts.forEach((e => {
                                        switch (e.transformType) {
                                        case l.CROP:
                                            t.push(pe(e));
                                            break;
                                        case l.LEGACY_CROP:
                                            t.push(fe(e));
                                            break;
                                        case l.LEGACY_FILL:
                                            let i = be(e);
                                            e.upscale && (i += _e(e)),
                                            t.push(i);
                                            break;
                                        case l.FIT:
                                            let n = ue(e);
                                            e.upscale && (n += _e(e)),
                                            t.push(n);
                                            break;
                                        case l.FILL:
                                            let r = me(e);
                                            e.upscale && (r += _e(e)),
                                            t.push(r);
                                            break;
                                        case l.FILL_FOCAL:
                                            let o = ge(e);
                                            e.upscale && (o += _e(e)),
                                            t.push(o)
                                        }
                                    }
                                    ));
                                    let i = t.join("/");
                                    return e.quality && (i += Te(e)),
                                    e.unsharpMask && (i += Ee(e.unsharpMask)),
                                    e.progressive || (i += Le(e)),
                                    e.watermark && (i += we(e)),
                                    e.filters && (i += Object.keys(e.filters).map((t => ve[t](e.filters))).join("")),
                                    e.fileType !== v.GIF && (e.encoding === A.AVIF ? (i += Oe(e),
                                    i += Ie(e)) : e.encoding === A.PAVIF ? (i += Ce(e),
                                    i += Ie(e)) : e.autoEncode && (i += Ae(e))),
                                    e.src?.isAnimated && e.transformed && (i += Re(e)),
                                    `${e.src.id}/${n}/${i}/${e.fileName}.${e.preferredExtension}`
                                }(o)
                            }
                            return t.id
                        }
                        const Me = {
                            [d.CENTER]: "50% 50%",
                            [d.TOP_LEFT]: "0% 0%",
                            [d.TOP_RIGHT]: "100% 0%",
                            [d.TOP]: "50% 0%",
                            [d.BOTTOM_LEFT]: "0% 100%",
                            [d.BOTTOM_RIGHT]: "100% 100%",
                            [d.BOTTOM]: "50% 100%",
                            [d.RIGHT]: "100% 50%",
                            [d.LEFT]: "0% 50%"
                        }
                          , Se = Object.entries(Me).reduce(( (e, [t,i]) => (e[i] = t,
                        e)), {})
                          , xe = [h.TILE, h.TILE_HORIZONTAL, h.TILE_VERTICAL, h.LEGACY_BG_FIT_AND_TILE, h.LEGACY_BG_FIT_AND_TILE_HORIZONTAL, h.LEGACY_BG_FIT_AND_TILE_VERTICAL]
                          , Ge = [h.LEGACY_ORIGINAL_SIZE, h.ORIGINAL_SIZE, h.LEGACY_BG_NORMAL];
                        function Fe(e, t, {width: i, height: n}) {
                            return e === h.TILE && t.width > i && t.height > n
                        }
                        function Ne(e, {width: t, height: i}) {
                            if (!t || !i) {
                                const n = t || Math.min(980, e.width)
                                  , r = n / e.width;
                                return {
                                    width: n,
                                    height: i || e.height * r
                                }
                            }
                            return {
                                width: t,
                                height: i
                            }
                        }
                        function Pe(e, t, i, n="center") {
                            const r = {
                                img: {},
                                container: {}
                            };
                            if (e === h.SCALE_TO_FILL) {
                                const e = t.focalPoint && function(e) {
                                    const t = `${e.x}% ${e.y}%`;
                                    return Se[t] || ""
                                }(t.focalPoint)
                                  , o = e || n;
                                t.focalPoint && !e ? r.img = {
                                    objectPosition: ke(t, i, t.focalPoint)
                                } : r.img = {
                                    objectPosition: Me[o]
                                }
                            } else
                                [h.LEGACY_ORIGINAL_SIZE, h.ORIGINAL_SIZE].includes(e) ? r.img = {
                                    objectFit: "none",
                                    top: "auto",
                                    left: "auto",
                                    right: "auto",
                                    bottom: "auto"
                                } : xe.includes(e) && (r.container = {
                                    backgroundSize: `${t.width}px ${t.height}px`
                                });
                            return r
                        }
                        function ke(e, t, i) {
                            const {width: n, height: r} = e
                              , {width: o, height: s} = t
                              , {x: a, y: c} = i;
                            if (!o || !s)
                                return `${a}% ${c}%`;
                            const h = Math.max(o / n, s / r)
                              , l = n * h
                              , d = r * h
                              , u = Math.max(0, Math.min(l - o, l * (a / 100) - o / 2))
                              , m = Math.max(0, Math.min(d - s, d * (c / 100) - s / 2));
                            return `${u && Math.floor(u / (l - o) * 100)}% ${m && Math.floor(m / (d - s) * 100)}%`
                        }
                        const Be = {
                            width: "100%",
                            height: "100%"
                        };
                        function He(e, t, i, n={}) {
                            const {autoEncode: r=!0, isSEOBot: o, shouldLoadHQImage: s, hasAnimation: a, allowAnimatedTransform: c, encoding: l} = n;
                            if (!M(e, t, i))
                                return _;
                            const d = void 0 === c || c
                              , u = S(t.id, a, d);
                            if (!u || s)
                                return $e(e, t, i, {
                                    ...n,
                                    autoEncode: r,
                                    useSrcset: u
                                });
                            const m = {
                                ...i,
                                ...Ne(t, i)
                            }
                              , {alignment: g, htmlTag: p} = m
                              , f = Fe(e, t, m)
                              , b = function(e, t, {width: i, height: n}, r=!1) {
                                if (r)
                                    return {
                                        width: i,
                                        height: n
                                    };
                                const o = !Ge.includes(e)
                                  , s = Fe(e, t, {
                                    width: i,
                                    height: n
                                })
                                  , a = !s && xe.includes(e)
                                  , c = a ? t.width : i
                                  , h = a ? t.height : n
                                  , l = o ? function(e, t) {
                                    return e > 900 ? t ? .05 : .15 : e > 500 ? t ? .1 : .18 : e > 200 ? .25 : 1
                                }(c, x(t.id)) : 1;
                                return {
                                    width: s ? 1920 : c * l,
                                    height: h * l
                                }
                            }(e, t, m, o)
                              , T = function(e, t, i) {
                                return i ? 0 : xe.includes(t) ? 1 : e > 200 ? 2 : 3
                            }(m.width, e, o)
                              , I = function(e, t) {
                                const i = xe.includes(e) && !t;
                                return e === h.SCALE_TO_FILL || i ? h.SCALE_TO_FIT : e
                            }(e, f)
                              , E = Pe(e, t, i, g)
                              , {uri: L} = $e(I, t, {
                                ...b,
                                alignment: g,
                                htmlTag: p
                            }, {
                                autoEncode: r,
                                filters: T ? {
                                    blur: T
                                } : {},
                                hasAnimation: a,
                                allowAnimatedTransform: d,
                                encoding: l
                            })
                              , {attr: w={}, css: v} = $e(e, t, {
                                ...m,
                                alignment: g,
                                htmlTag: p
                            }, {});
                            return v.img = v.img || {},
                            v.container = v.container || {},
                            Object.assign(v.img, E.img, Be),
                            Object.assign(v.container, E.container),
                            {
                                uri: L,
                                css: v,
                                attr: w,
                                transformed: !0
                            }
                        }
                        function $e(e, t, i, n) {
                            let r = {};
                            if (M(e, t, i)) {
                                const o = de(e, t, i)
                                  , s = le(e, t, o, n);
                                r.uri = ye(e, t, o, n, s),
                                n?.useSrcset && (r.srcset = function(e, t, i, n, r) {
                                    const o = i.pixelAspectRatio || 1;
                                    return {
                                        dpr: [`${1 === o ? r.uri : ye(e, t, {
                                            ...i,
                                            pixelAspectRatio: 1
                                        }, n)} 1x`, `${2 === o ? r.uri : ye(e, t, {
                                            ...i,
                                            pixelAspectRatio: 2
                                        }, n)} 2x`]
                                    }
                                }(e, t, o, n, r)),
                                Object.assign(r, function(e, t) {
                                    let i;
                                    return i = t.htmlTag === g.BG ? ee : t.htmlTag === g.SVG ? re : ne,
                                    i(e, t)
                                }(s, o), {
                                    transformed: s.transformed
                                })
                            } else
                                r = _;
                            return r
                        }
                        function Ue(e, t, i, n) {
                            if (M(e, t, i)) {
                                const r = de(e, t, i);
                                return {
                                    uri: ye(e, t, r, n || {}, le(e, t, r, n))
                                }
                            }
                            return {
                                uri: ""
                            }
                        }
                        const We = "https://static.wixstatic.com/media/"
                          , ze = /^media\//i
                          , Ye = "undefined" != typeof window ? window.devicePixelRatio : 1
                          , De = (e, t) => {
                            const i = t && t.baseHostURL;
                            return i ? `${i}${e}` : (e => ze.test(e) ? `https://static.wixstatic.com/${e}` : `${We}${e}`)(e)
                        }
                        ;
                        Q();
                        const Ve = (e, t, i) => {
                            const {displayMode: n, uri: r, width: o, height: s, name: a, crop: c, focalPoint: h, alignType: l, quality: d, upscaleMethod: u, hasAnimation: m, allowAnimatedTransform: g, encoding: p} = e
                              , {srcset: f, css: b, uri: _} = $e(n, {
                                id: r,
                                width: o,
                                height: s,
                                name: a,
                                crop: c,
                                focalPoint: h
                            }, {
                                width: t,
                                height: i,
                                alignment: l
                            }, {
                                focalPoint: h,
                                name: a,
                                quality: d?.quality,
                                upscaleMethod: u,
                                hasAnimation: m,
                                allowAnimatedTransform: g,
                                useSrcset: !0,
                                encoding: p
                            })
                              , T = f?.dpr?.map((e => /^[a-z]+:/.test(e) ? e : `${qe}${e}`))
                              , I = `${qe}${_}`
                              , E = T?.join(", ");
                            return {
                                fallbackSrc: I,
                                srcset: E,
                                css: b
                            }
                        }
                        ;
                        Q();
                        const je = {
                            getScaleToFitImageURL: function(e, t, i, n, r, o) {
                                const s = Ue(h.SCALE_TO_FIT, {
                                    id: e,
                                    width: t,
                                    height: i,
                                    name: o && o.name
                                }, {
                                    width: n,
                                    height: r,
                                    htmlTag: g.IMG,
                                    alignment: d.CENTER,
                                    pixelAspectRatio: o?.devicePixelRatio ?? Ye
                                }, o);
                                return De(s.uri, o)
                            },
                            getScaleToFillImageURL: function(e, t, i, n, r, o) {
                                const s = Ue(h.SCALE_TO_FILL, {
                                    id: e,
                                    width: t,
                                    height: i,
                                    name: o && o.name,
                                    focalPoint: {
                                        x: o && o.focalPoint && o.focalPoint.x,
                                        y: o && o.focalPoint && o.focalPoint.y
                                    }
                                }, {
                                    width: n,
                                    height: r,
                                    htmlTag: g.IMG,
                                    alignment: d.CENTER,
                                    pixelAspectRatio: o?.devicePixelRatio ?? Ye
                                }, o);
                                return De(s.uri, o)
                            },
                            getCropImageURL: function(e, t, i, n, r, o, s, a, c, l) {
                                const u = Ue(h.SCALE_TO_FILL, {
                                    id: e,
                                    width: t,
                                    height: i,
                                    name: l && l.name,
                                    crop: {
                                        x: n,
                                        y: r,
                                        width: o,
                                        height: s
                                    }
                                }, {
                                    width: a,
                                    height: c,
                                    htmlTag: g.IMG,
                                    alignment: d.CENTER,
                                    pixelAspectRatio: l?.devicePixelRatio ?? Ye
                                }, l);
                                return De(u.uri, l)
                            }
                        }
                          , qe = We
                    }
                    ,
                    72757: (e, t, i) => {
                        (0,
                        i(30012).Rr)()
                    }
                    ,
                    98700: (e, t, i) => {
                        var n = i(30012)
                          , r = i(20826);
                        ( (e=window) => {
                            const {mediaServices: t, environmentConsts: i, requestUrl: o, staticVideoUrl: s} = e.customElementNamespace;
                            (0,
                            n.EH)(e, t, {
                                ...i,
                                prefersReducedMotion: (0,
                                r.O)(window, o),
                                staticVideoUrl: s
                            }),
                            (0,
                            n.jh)(e),
                            (0,
                            n.p7)(e, t, i)
                        }
                        )(),
                        window.resolveExternalsRegistryModule("imageClientApi")
                    }
                    ,
                    30012: (e, t, i) => {
                        i.d(t, {
                            Rr: () => F,
                            Aq: () => h,
                            p7: () => R,
                            jh: () => P,
                            EH: () => U,
                            KU: () => c,
                            _o: () => a,
                            vk: () => l,
                            NL: () => y,
                            yO: () => A
                        });
                        var n = i(17709)
                          , r = i.n(n);
                        const o = (e, t, i) => {
                            let n = 1
                              , r = 0;
                            for (let o = 0; o < e.length; o++) {
                                const s = e[o];
                                if (s > t)
                                    return !1;
                                if (r += s,
                                r > t && (n++,
                                r = s,
                                n > i))
                                    return !1
                            }
                            return !0
                        }
                          , s = (e, t, i) => {
                            let n = -1 / 0;
                            const r = e.map((e => (e.height + t > n && (n = e.height + t),
                            e.height + t)));
                            let s = n
                              , a = n * e.length
                              , c = n;
                            for (; s < a; ) {
                                const e = Math.floor((s + a) / 2);
                                o(r, e, i) ? a = e : s = e + 1,
                                c = s
                            }
                            return c - t
                        }
                        ;
                        function a() {
                            class e extends HTMLElement {
                                constructor() {
                                    super(...arguments),
                                    this.containerWidth = 0,
                                    this.isActive = !1,
                                    this.isDuringCalc = !1,
                                    this.attachObservers = () => {
                                        this.mutationObserver?.observe(this, {
                                            childList: !0,
                                            subtree: !0
                                        }),
                                        this.containerWidthObserver?.observe(this),
                                        Array.from(this.children).forEach((e => {
                                            this.handleItemAdded(e)
                                        }
                                        ))
                                    }
                                    ,
                                    this.detachHeightCalcObservers = () => {
                                        this.mutationObserver?.disconnect(),
                                        this.containerWidthObserver?.disconnect(),
                                        this.childResizeObserver?.disconnect()
                                    }
                                    ,
                                    this.recalcHeight = () => {
                                        this.isActive && r().measure(( () => {
                                            if (!this.isActive || this.isDuringCalc)
                                                return;
                                            this.isDuringCalc = !0;
                                            const e = getComputedStyle(this)
                                              , t = s(this.itemsHeights, this.getRowGap(e), this.getColumnCount(e));
                                            this.isDuringCalc = !1,
                                            r().mutate(( () => {
                                                this.setContainerHeight(t),
                                                this.style.setProperty("visibility", null)
                                            }
                                            ))
                                        }
                                        ))
                                    }
                                    ,
                                    this.cleanUp = () => {
                                        this.detachHeightCalcObservers(),
                                        this.removeContainerHeight(),
                                        this.isActiveObserver?.disconnect()
                                    }
                                    ,
                                    this.handleItemAdded = e => {
                                        e instanceof window.HTMLElement && this.childResizeObserver?.observe(e)
                                    }
                                    ,
                                    this.handleItemRemoved = e => {
                                        e instanceof window.HTMLElement && this.childResizeObserver?.unobserve(e)
                                    }
                                    ,
                                    this.createObservers = () => {
                                        this.containerWidthObserver = new ResizeObserver((e => {
                                            const t = e[0];
                                            if (t.contentRect.width !== this.containerWidth) {
                                                if (0 === this.containerWidth)
                                                    return void (this.containerWidth = t.contentRect.width);
                                                this.containerWidth = t.contentRect.width,
                                                this.recalcHeight()
                                            }
                                        }
                                        )),
                                        this.mutationObserver = new MutationObserver((e => {
                                            e.forEach((e => {
                                                Array.from(e.removedNodes).forEach(this.handleItemRemoved),
                                                Array.from(e.addedNodes).forEach(this.handleItemAdded)
                                            }
                                            )),
                                            this.recalcHeight()
                                        }
                                        )),
                                        this.childResizeObserver = new ResizeObserver(( () => {
                                            this.recalcHeight()
                                        }
                                        )),
                                        this.isActiveObserver = new ResizeObserver(( () => {
                                            this.setIsActive()
                                        }
                                        ))
                                    }
                                }
                                setContainerHeight(e) {
                                    this.style.setProperty("--flex-columns-height", `${e}px`)
                                }
                                removeContainerHeight() {
                                    this.style.removeProperty("--flex-columns-height")
                                }
                                getColumnCount(e) {
                                    const t = e.getPropertyValue("--flex-column-count");
                                    return parseInt(t, 10)
                                }
                                getRowGap(e) {
                                    const t = e.getPropertyValue("row-gap");
                                    return parseInt(t || "0", 10)
                                }
                                activate() {
                                    this.isActive = !0,
                                    this.attachObservers(),
                                    this.recalcHeight()
                                }
                                deactivate() {
                                    this.isActive = !1,
                                    this.detachHeightCalcObservers(),
                                    this.removeContainerHeight()
                                }
                                calcActive() {
                                    return "multi-column-layout" === getComputedStyle(this).getPropertyValue("--container-layout-type")
                                }
                                get itemsHeights() {
                                    return Array.from(this.children).map((e => {
                                        const t = getComputedStyle(e);
                                        let i = parseFloat(t.height || "0");
                                        return i += parseFloat(t.marginTop || "0"),
                                        i += parseFloat(t.marginBottom || "0"),
                                        {
                                            height: i
                                        }
                                    }
                                    ))
                                }
                                setIsActive() {
                                    const e = this.calcActive();
                                    this.isActive !== e && (e ? this.activate() : this.deactivate())
                                }
                                connectedCallback() {
                                    this.cleanUp(),
                                    this.createObservers(),
                                    this.setIsActive(),
                                    window.document.body && this.isActiveObserver?.observe(window.document.body)
                                }
                                disconnectedCallback() {
                                    this.cleanUp()
                                }
                            }
                            return e
                        }
                        const c = "multi-column-layouter"
                          , h = () => {
                            const e = {
                                observedElementToRelayoutTarget: new Map,
                                getLayoutTargets(t) {
                                    const i = new Set;
                                    return t.forEach((t => i.add(e.observedElementToRelayoutTarget.get(t)))),
                                    i
                                },
                                observe: i => {
                                    e.observedElementToRelayoutTarget.set(i, i),
                                    t.observe(i)
                                }
                                ,
                                unobserve: i => {
                                    e.observedElementToRelayoutTarget.delete(i),
                                    t.unobserve(i)
                                }
                                ,
                                observeChild: (i, n) => {
                                    e.observedElementToRelayoutTarget.set(i, n),
                                    t.observe(i)
                                }
                                ,
                                unobserveChild: i => {
                                    e.observedElementToRelayoutTarget.delete(i),
                                    t.unobserve(i)
                                }
                            }
                              , t = new window.ResizeObserver((t => {
                                e.getLayoutTargets(t.map((e => e.target))).forEach((e => e.reLayout()))
                            }
                            ));
                            return e
                        }
                          , l = (e, t=window) => {
                            let i = !1;
                            return (...n) => {
                                i || (i = !0,
                                t.requestAnimationFrame(( () => {
                                    i = !1,
                                    e(...n)
                                }
                                )))
                            }
                        }
                        ;
                        function d(...e) {
                            let t = e[0];
                            for (let i = 1; i < e.length; ++i)
                                t = `${t.replace(/\/$/, "")}/${e[i].replace(/^\//, "")}`;
                            return t
                        }
                        var u = i(22538);
                        const m = (e, t, i) => {
                            if (/(^https?)|(^data)|(^blob)|(^\/\/)/.test(e))
                                return e;
                            let n = `${t}/`;
                            return e && (/^micons\//.test(e) ? n = i : "ico" === /[^.]+$/.exec(e)[0] && (n = n.replace("media", "ficons"))),
                            n + e
                        }
                          , g = e => {
                            const t = window.location.search.split("&").map((e => e.split("="))).find((e => e[0].toLowerCase().includes("devicepixelratio")));
                            return (t ? Number(t[1]) : null) || e || 1
                        }
                        ;
                        const p = {
                            columnCount: 1,
                            columns: 1,
                            fontWeight: 1,
                            lineHeight: 1,
                            opacity: 1,
                            zIndex: 1,
                            zoom: 1
                        }
                          , f = (e, t) => e && t && Object.keys(t).forEach((i => e.setAttribute(i, t[i])))
                          , b = (e, t) => e && t && Object.keys(t).forEach((i => {
                            const n = t[i];
                            void 0 !== n ? e.style[i] = ( (e, t) => "number" != typeof t || p[e] ? t : `${t}px`)(i, n) : e.style.removeProperty(i)
                        }
                        ))
                          , _ = (e, t) => e && t && Object.keys(t).forEach((i => {
                            e.style.setProperty(i, t[i])
                        }
                        ))
                          , T = (e, t, i=!0) => {
                            return e && i ? (n = e.dataset[t]) ? "true" === n || "false" !== n && ("null" === n ? null : "" + +n === n ? +n : n) : n : e.dataset[t];
                            var n
                        }
                          , I = (e, t) => e && t && Object.assign(e.dataset, t)
                          , E = e => e || document.documentElement.clientHeight || window.innerHeight || 0
                          , L = {
                            fit: "contain",
                            fill: "cover"
                        };
                        const w = (e=window) => ({
                            measure: function(e, t, i, {containerId: n, bgEffectName: r}, o) {
                                const s = i[e]
                                  , a = i[n]
                                  , {width: c, height: h} = o.getMediaDimensionsByEffect(r, a.offsetWidth, a.offsetHeight, E(o.getScreenHeightOverride?.()));
                                t.width = c,
                                t.height = h,
                                t.currentSrc = s.style.backgroundImage,
                                t.bgEffectName = s.dataset.bgEffectName
                            },
                            patch: function(t, i, n, r, o) {
                                const s = n[t];
                                r.targetWidth = i.width,
                                r.targetHeight = i.height;
                                const a = ( (e, t, i) => {
                                    const {targetWidth: n, targetHeight: r, imageData: o, filters: s, displayMode: a=u.fittingTypes.SCALE_TO_FILL} = e;
                                    if (!n || !r || !o.uri)
                                        return {
                                            uri: "",
                                            css: {}
                                        };
                                    const {width: c, height: h, crop: l, name: d, focalPoint: p, upscaleMethod: f, quality: b, devicePixelRatio: _=t.devicePixelRatio} = o
                                      , T = {
                                        filters: s,
                                        upscaleMethod: f,
                                        ...b,
                                        hasAnimation: e?.hasAnimation || o?.hasAnimation
                                    }
                                      , I = g(_)
                                      , E = {
                                        id: o.uri,
                                        width: c,
                                        height: h,
                                        ...l && {
                                            crop: l
                                        },
                                        ...p && {
                                            focalPoint: p
                                        },
                                        ...d && {
                                            name: d
                                        }
                                    }
                                      , L = {
                                        width: n,
                                        height: r,
                                        htmlTag: i || "img",
                                        pixelAspectRatio: I,
                                        alignment: e.alignType || u.alignTypes.CENTER
                                    }
                                      , w = (0,
                                    u.getData)(a, E, L, T);
                                    return w.uri = m(w.uri, t.staticMediaUrl, t.mediaRootUrl),
                                    w
                                }
                                )(r, o, "bg");
                                !function(e="", t) {
                                    return !e.includes(t) || !!e != !!t
                                }(i.currentSrc, a.uri) ? b(s, a.css.container) : function(t, i) {
                                    const n = {
                                        backgroundImage: `url("${i.uri}")`,
                                        ...i.css.container
                                    }
                                      , r = new e.Image;
                                    r.onload = b.bind(null, t, n),
                                    r.src = i.uri
                                }(s, a)
                            }
                        });
                        const v = (e, t, i) => {
                            void 0 === e.customElements.get(t) && e.customElements.define(t, i)
                        }
                        ;
                        function A(e, t=window) {
                            class i extends t.HTMLElement {
                                constructor() {
                                    super()
                                }
                                reLayout() {}
                                connectedCallback() {
                                    this.observeResize(),
                                    this.reLayout()
                                }
                                disconnectedCallback() {
                                    this.unobserveResize(),
                                    this.unobserveChildren()
                                }
                                observeResize() {
                                    e.resizeService.observe(this)
                                }
                                unobserveResize() {
                                    e.resizeService.unobserve(this)
                                }
                                observeChildren(e) {
                                    this.childListObserver || (this.childListObserver = new t.MutationObserver(( () => this.reLayout()))),
                                    this.childListObserver.observe(e, {
                                        childList: !0
                                    })
                                }
                                observeChildAttributes(e, i=[]) {
                                    this.childrenAttributesObservers || (this.childrenAttributesObservers = []);
                                    const n = new t.MutationObserver(( () => this.reLayout()));
                                    n.observe(e, {
                                        attributeFilter: i
                                    }),
                                    this.childrenAttributesObservers.push(n)
                                }
                                observeChildResize(t) {
                                    this.childrenResizeObservers || (this.childrenResizeObservers = []),
                                    e.resizeService.observeChild(t, this),
                                    this.childrenResizeObservers.push(t)
                                }
                                unobserveChildrenResize() {
                                    this.childrenResizeObservers && (this.childrenResizeObservers.forEach((t => {
                                        e.resizeService.unobserveChild(t)
                                    }
                                    )),
                                    this.childrenResizeObservers = null)
                                }
                                unobserveChildren() {
                                    if (this.childListObserver && (this.childListObserver.disconnect(),
                                    this.childListObserver = null),
                                    this.childrenAttributesObservers) {
                                        for (let e of this.childrenAttributesObservers)
                                            e.disconnect(),
                                            e = null;
                                        this.childrenAttributesObservers = null
                                    }
                                    this.unobserveChildrenResize()
                                }
                            }
                            return i
                        }
                        const O = e => {
                            if (e.customElementNamespace || (e.customElementNamespace = {}),
                            void 0 === e.customElementNamespace.WixElement) {
                                const t = A({
                                    resizeService: h()
                                }, e);
                                return e.customElementNamespace.WixElement = t,
                                t
                            }
                            return e.customElementNamespace.WixElement
                        }
                          , C = "wix-bg-image"
                          , R = (e=globalThis.window, t={}, i={
                            experiments: {}
                        }) => {
                            if (e && void 0 === e.customElements.get(C)) {
                                const n = function(e, t, i, n=window) {
                                    const r = w(n);
                                    return class extends e {
                                        constructor() {
                                            super()
                                        }
                                        reLayout() {
                                            if (function(e) {
                                                return e.isExperimentOpen("specs.thunderbolt.tb_stop_client_images") || e.isExperimentOpen("specs.thunderbolt.final_force_webp") || e.isExperimentOpen("specs.thunderbolt.final_force_no_webp")
                                            }(t))
                                                return;
                                            const e = {}
                                              , o = {}
                                              , s = this.getAttribute("id")
                                              , a = JSON.parse(this.dataset.tiledImageInfo)
                                              , {bgEffectName: c} = this.dataset
                                              , {containerId: h} = a
                                              , l = n.document.getElementById(h);
                                            e[s] = this,
                                            e[h] = l,
                                            a.displayMode = a.imageData.displayMode,
                                            t.mutationService.measure(( () => {
                                                r.measure(s, o, e, {
                                                    containerId: h,
                                                    bgEffectName: c
                                                }, t)
                                            }
                                            )),
                                            t.mutationService.mutate(( () => {
                                                r.patch(s, o, e, a, i, t)
                                            }
                                            ))
                                        }
                                        attributeChangedCallback(e, t) {
                                            t && this.reLayout()
                                        }
                                        disconnectedCallback() {
                                            super.disconnectedCallback()
                                        }
                                        static get observedAttributes() {
                                            return ["data-tiled-image-info"]
                                        }
                                    }
                                }(O(e), t, i, e);
                                v(e, C, n)
                            }
                        }
                        ;
                        function y(e, t, i=window) {
                            const n = {
                                width: void 0,
                                height: void 0,
                                left: void 0
                            };
                            return class extends e {
                                constructor() {
                                    super()
                                }
                                reLayout() {
                                    const {containerId: e, pageId: r, useCssVars: o, bgEffectName: s} = this.dataset
                                      , a = this.closest(`#${e}`) || i.document.getElementById(`${e}`)
                                      , c = this.closest(`#${r}`) || i.document.getElementById(`${r}`)
                                      , h = {};
                                    t.mutationService.measure(( () => {
                                        const e = "fixed" === i.getComputedStyle(this).position
                                          , n = E(t.getScreenHeightOverride?.())
                                          , r = a.getBoundingClientRect()
                                          , l = t.getMediaDimensionsByEffect(s, r.width, r.height, n)
                                          , {hasParallax: d} = l
                                          , u = c && (i.getComputedStyle(c).transition || "").includes("transform")
                                          , {width: m, height: g} = l
                                          , p = `${m}px`
                                          , f = `${g}px`;
                                        let b = (r.width - m) / 2 + "px";
                                        if (e) {
                                            const e = i.document.documentElement.clientLeft;
                                            b = u ? a.offsetLeft - e + "px" : r.left - e + "px"
                                        }
                                        const _ = e || d ? 0 : (r.height - g) / 2 + "px"
                                          , T = o ? {
                                            "--containerW": p,
                                            "--containerH": f,
                                            "--containerL": b,
                                            "--screenH_val": `${n}`
                                        } : {
                                            width: p,
                                            height: f,
                                            left: b,
                                            top: _
                                        };
                                        Object.assign(h, T)
                                    }
                                    )),
                                    t.mutationService.mutate(( () => {
                                        o ? (b(this, n),
                                        _(this, h)) : b(this, h)
                                    }
                                    ))
                                }
                                connectedCallback() {
                                    super.connectedCallback(),
                                    t.windowResizeService.observe(this)
                                }
                                disconnectedCallback() {
                                    super.disconnectedCallback(),
                                    t.windowResizeService.unobserve(this)
                                }
                                attributeChangedCallback(e, t) {
                                    t && this.reLayout()
                                }
                                static get observedAttributes() {
                                    return ["data-is-full-height", "data-container-size"]
                                }
                            }
                        }
                        const M = "__more__"
                          , S = "moreContainer"
                          , x = (e=window) => {
                            const t = (e, t, i, n, r, o, s, a) => {
                                if (e -= r * (s ? n.length : n.length - 1),
                                e -= a.left + a.right,
                                t && (n = n.map(( () => o))),
                                n.some((e => 0 === e)))
                                    return null;
                                let c = 0;
                                const h = n.reduce(( (e, t) => e + t), 0);
                                if (h > e)
                                    return null;
                                if (t) {
                                    if (i) {
                                        const t = Math.floor(e / n.length)
                                          , i = n.map(( () => t));
                                        if (c = t * n.length,
                                        c < e) {
                                            const t = Math.floor(e - c);
                                            n.forEach(( (e, n) => {
                                                n <= t - 1 && i[n]++
                                            }
                                            ))
                                        }
                                        return i
                                    }
                                    return n
                                }
                                if (i) {
                                    const t = Math.floor((e - h) / n.length);
                                    c = 0;
                                    const i = n.map((e => (c += e + t,
                                    e + t)));
                                    if (c < e) {
                                        const t = Math.floor(e - c);
                                        n.forEach(( (e, n) => {
                                            n <= t - 1 && i[n]++
                                        }
                                        ))
                                    }
                                    return i
                                }
                                return n
                            }
                              , i = e => Math.round(e)
                              , n = e => {
                                const t = parseFloat(e);
                                return isFinite(t) ? t : 0
                            }
                              , r = t => t.getBoundingClientRect().top > e.innerHeight / 2
                              , o = (e, t, i, n, r) => {
                                const {width: o, height: s, alignButtons: a, hoverListPosition: c, menuItemContainerExtraPixels: h} = t
                                  , l = t.absoluteLeft
                                  , d = ( (e, t, i, n, r, o, s, a, c, h) => {
                                    let l = "0px"
                                      , d = "auto";
                                    const u = o.left
                                      , m = o.width;
                                    if ("left" === t ? l = "left" === r ? 0 : `${u + e.left}px` : "right" === t ? (d = "right" === r ? 0 : n - u - m - e.right + "px",
                                    l = "auto") : "left" === r ? l = `${u + (m + e.left - i) / 2}px` : "right" === r ? (l = "auto",
                                    d = (m + e.right - (i + e.width)) / 2 + "px") : l = `${e.left + u + (m - (i + e.width)) / 2}px`,
                                    "auto" !== l) {
                                        const e = s + parseInt(l, 10);
                                        e + h > c ? (l = "auto",
                                        d = 0) : l = e < 0 ? 0 : l
                                    }
                                    "auto" !== d && (d = a - parseInt(d, 10) > c ? 0 : d);
                                    return {
                                        moreContainerLeft: l,
                                        moreContainerRight: d
                                    }
                                }
                                )(h, a, n, o, c, i, l, l + o, t.bodyClientWidth, r);
                                return {
                                    left: d.moreContainerLeft,
                                    right: d.moreContainerRight,
                                    top: t.needToOpenMenuUp ? "auto" : `${s}px`,
                                    bottom: t.needToOpenMenuUp ? `${s}px` : "auto"
                                }
                            }
                              , s = e => !isNaN(parseFloat(e)) && isFinite(e);
                            return {
                                measure: (o, s) => {
                                    const a = {}
                                      , c = {};
                                    c[o] = s;
                                    let h = 1;
                                    const l = s.getRootNode().querySelector("#site-root");
                                    l && (h = l.getBoundingClientRect().width / l.offsetWidth);
                                    const d = (e => {
                                        const t = +T(e, "numItems");
                                        return t <= 0 || t > Number.MAX_SAFE_INTEGER ? [] : new Array(t).fill(0).map(( (e, t) => String(t)))
                                    }
                                    )(c[o])
                                      , u = (e => ["moreContainer", "itemsContainer", "dropWrapper"].concat(e, [M]))(d);
                                    u.forEach((e => {
                                        const t = `${o}${e}`;
                                        c[t] = s.getRootNode().getElementById(`${t}`)
                                    }
                                    )),
                                    a.children = ( (e, t, n, r) => {
                                        const o = {};
                                        return n.forEach((n => {
                                            const s = `${e}${n}`
                                              , a = t[s];
                                            a && (o[s] = {
                                                width: a.offsetWidth,
                                                boundingClientRectWidth: i(a.getBoundingClientRect().width / r),
                                                height: a.offsetHeight
                                            })
                                        }
                                        )),
                                        o
                                    }
                                    )(o, c, u, h);
                                    const m = c[o]
                                      , g = c[`${o}itemsContainer`]
                                      , p = g.childNodes
                                      , f = c[`${o}moreContainer`]
                                      , b = f.childNodes
                                      , _ = T(m, "stretchButtonsToMenuWidth")
                                      , I = T(m, "sameWidthButtons")
                                      , E = m.getBoundingClientRect();
                                    a.absoluteLeft = E.left,
                                    a.bodyClientWidth = e.document.body.clientWidth,
                                    a.alignButtons = T(m, "dropalign"),
                                    a.hoverListPosition = T(m, "drophposition"),
                                    a.menuBorderY = parseInt(T(m, "menuborderY"), 10),
                                    a.ribbonExtra = parseInt(T(m, "ribbonExtra"), 10),
                                    a.ribbonEls = parseInt(T(m, "ribbonEls"), 10),
                                    a.labelPad = parseInt(T(m, "labelPad"), 10),
                                    a.menuButtonBorder = parseInt(T(m, "menubtnBorder"), 10),
                                    a.menuItemContainerMargins = (t => {
                                        const i = t.lastChild
                                          , n = e.getComputedStyle(i);
                                        return (parseInt(n.marginLeft, 10) || 0) + (parseInt(n.marginRight, 10) || 0)
                                    }
                                    )(g),
                                    a.menuItemContainerExtraPixels = ( (t, i) => {
                                        const r = e.getComputedStyle(t);
                                        let o = n(r.borderTopWidth) + n(r.paddingTop)
                                          , s = n(r.borderBottomWidth) + n(r.paddingBottom)
                                          , a = n(r.borderLeftWidth) + n(r.paddingLeft)
                                          , c = n(r.borderRightWidth) + n(r.paddingRight);
                                        return i && (o += n(r.marginTop),
                                        s += n(r.marginBottom),
                                        a += n(r.marginLeft),
                                        c += n(r.marginRight)),
                                        {
                                            top: o,
                                            bottom: s,
                                            left: a,
                                            right: c,
                                            height: o + s,
                                            width: a + c
                                        }
                                    }
                                    )(g, !0),
                                    a.needToOpenMenuUp = r(m),
                                    a.menuItemMarginForAllChildren = !_ || "false" !== g.getAttribute("data-marginAllChildren"),
                                    a.moreSubItem = [],
                                    a.labelWidths = {},
                                    a.linkIds = {},
                                    a.parentId = {},
                                    a.menuItems = {},
                                    a.labels = {},
                                    b.forEach(( (t, i) => {
                                        a.parentId[t.id] = T(t, "parentId");
                                        const n = T(t, "dataId");
                                        a.menuItems[n] = {
                                            dataId: n,
                                            parentId: T(t, "parentId"),
                                            moreDOMid: t.id,
                                            moreIndex: i
                                        },
                                        c[t.id] = t;
                                        const r = t.querySelector("p");
                                        c[r.id] = r,
                                        a.labels[r.id] = {
                                            width: r.offsetWidth,
                                            height: r.offsetHeight,
                                            left: r.offsetLeft,
                                            lineHeight: parseInt(e.getComputedStyle(r).fontSize, 10)
                                        },
                                        a.moreSubItem.push(t.id)
                                    }
                                    )),
                                    p.forEach(( (e, t) => {
                                        const n = T(e, "dataId");
                                        a.menuItems[n] = a.menuItems[n] || {},
                                        a.menuItems[n].menuIndex = t,
                                        a.menuItems[n].menuDOMid = e.id,
                                        a.children[e.id].left = e.offsetLeft;
                                        const r = e.querySelector("p");
                                        c[r.id] = r,
                                        a.labelWidths[r.id] = ( (e, t) => i(e.getBoundingClientRect().width / t))(r, h);
                                        const o = e.querySelector("p");
                                        c[o.id] = o,
                                        a.linkIds[e.id] = o.id
                                    }
                                    ));
                                    const L = m.offsetHeight;
                                    a.height = L,
                                    a.width = m.offsetWidth,
                                    a.lineHeight = ( (e, t) => e - t.menuBorderY - t.labelPad - t.ribbonEls - t.menuButtonBorder - t.ribbonExtra + "px")(L, a);
                                    const w = ( (e, i, n, r, o) => {
                                        const s = i.width;
                                        i.hasOriginalGapData = {},
                                        i.originalGapBetweenTextAndBtn = {};
                                        const a = o.map((t => {
                                            const n = r[e + t];
                                            let o;
                                            const s = T(n, "originalGapBetweenTextAndBtn");
                                            return void 0 === s ? (i.hasOriginalGapData[t] = !1,
                                            o = i.children[e + t].boundingClientRectWidth - i.labelWidths[`${e + t}label`],
                                            i.originalGapBetweenTextAndBtn[e + t] = o) : (i.hasOriginalGapData[t] = !0,
                                            o = parseFloat(s)),
                                            i.children[e + t].width > 0 ? Math.floor(i.labelWidths[`${e + t}label`] + o) : 0
                                        }
                                        ))
                                          , c = a.pop()
                                          , h = n.sameWidthButtons
                                          , l = n.stretchButtonsToMenuWidth;
                                        let d = !1;
                                        const u = i.menuItemContainerMargins
                                          , m = i.menuItemMarginForAllChildren
                                          , g = i.menuItemContainerExtraPixels
                                          , p = (e => e.reduce(( (e, t) => e > t ? e : t), -1 / 0))(a);
                                        let f = t(s, h, l, a, u, p, m, g);
                                        if (!f) {
                                            for (let e = 1; e <= a.length; e++)
                                                if (f = t(s, h, l, a.slice(0, -1 * e).concat(c), u, p, m, g),
                                                f) {
                                                    d = !0;
                                                    break
                                                }
                                            f || (d = !0,
                                            f = [c])
                                        }
                                        if (d) {
                                            const e = f[f.length - 1];
                                            for (f = f.slice(0, -1); f.length < o.length; )
                                                f.push(0);
                                            f[f.length - 1] = e
                                        }
                                        return {
                                            realWidths: f,
                                            moreShown: d
                                        }
                                    }
                                    )(o, a, {
                                        sameWidthButtons: I,
                                        stretchButtonsToMenuWidth: _
                                    }, c, d.concat(M));
                                    return a.realWidths = w.realWidths,
                                    a.isMoreShown = w.moreShown,
                                    a.menuItemIds = d,
                                    a.hoverState = T(f, "hover", !1),
                                    {
                                        measures: a,
                                        domNodes: c
                                    }
                                }
                                ,
                                patch: (e, t, i) => {
                                    const n = i[e];
                                    b(n, {
                                        overflowX: "visible"
                                    });
                                    const {menuItemIds: r, needToOpenMenuUp: a} = t
                                      , c = r.concat(M);
                                    I(n, {
                                        dropmode: a ? "dropUp" : "dropDown"
                                    });
                                    let h = 0;
                                    if (t.hoverState === M) {
                                        const e = t.realWidths.indexOf(0)
                                          , n = t.menuItems[(l = t.menuItems,
                                        d = t => t.menuIndex === e,
                                        Object.keys(l).find((e => d(l[e], e))))]
                                          , o = n.moreIndex
                                          , s = o === r.length - 1;
                                        n.moreDOMid && f(i[n.moreDOMid], {
                                            "data-listposition": s ? "dropLonely" : "top"
                                        }),
                                        Object.values(t.menuItems).filter((e => !!e.moreDOMid)).forEach((e => {
                                            if (e.moreIndex < o)
                                                b(i[e.moreDOMid], {
                                                    display: "none"
                                                });
                                            else {
                                                const i = `${e.moreDOMid}label`;
                                                h = Math.max(t.labels[i].width, h)
                                            }
                                        }
                                        ))
                                    } else
                                        t.hoverState && t.moreSubItem.forEach(( (i, n) => {
                                            const r = `${e + S + n}label`;
                                            h = Math.max(t.labels[r].width, h)
                                        }
                                        ));
                                    var l, d;
                                    ( (e, t, i, n) => {
                                        const {hoverState: r} = t;
                                        if ("-1" !== r) {
                                            const {menuItemIds: a} = t
                                              , c = a.indexOf(r);
                                            if (s(t.hoverState) || r === M) {
                                                if (!t.realWidths)
                                                    return;
                                                const r = Math.max(n, t.children[-1 !== c ? e + c : e + M].width)
                                                  , a = Math.max(n, t.children[`${e}dropWrapper`].width)
                                                  , h = ( (e, t) => e + 15 + t.menuBorderY + t.labelPad + t.menuButtonBorder)(0 !== t.moreSubItem.length ? t.labels[`${t.moreSubItem[0]}label`].lineHeight : 0, t);
                                                t.moreSubItem.forEach((e => {
                                                    b(i[e], {
                                                        minWidth: `${r}px`
                                                    }),
                                                    b(i[`${e}label`], {
                                                        minWidth: "0px",
                                                        lineHeight: `${h}px`
                                                    })
                                                }
                                                ));
                                                const l = s(t.hoverState) ? t.hoverState : "__more__"
                                                  , d = {
                                                    width: t.children[e + l].width,
                                                    left: t.children[e + l].left
                                                }
                                                  , u = o(0, t, d, r, a);
                                                b(i[`${e}${S}`], {
                                                    left: u.left,
                                                    right: u.right
                                                }),
                                                b(i[`${e}dropWrapper`], {
                                                    left: u.left,
                                                    right: u.right,
                                                    top: u.top,
                                                    bottom: u.bottom
                                                })
                                            }
                                        }
                                    }
                                    )(e, t, i, h),
                                    t.originalGapBetweenTextAndBtn && c.forEach((n => {
                                        t.hasOriginalGapData[n] || I(i[`${e}${n}`], {
                                            originalGapBetweenTextAndBtn: t.originalGapBetweenTextAndBtn[`${e}${n}`]
                                        })
                                    }
                                    )),
                                    ( (e, t, i, n) => {
                                        const {realWidths: r, height: o, menuItemContainerExtraPixels: s} = i;
                                        let a = 0
                                          , c = null
                                          , h = null;
                                        const l = i.lineHeight
                                          , d = o - s.height;
                                        for (let o = 0; o < n.length; o++) {
                                            const s = r[o]
                                              , u = s > 0
                                              , m = e + n[o];
                                            h = i.linkIds[m],
                                            u ? (a++,
                                            c = m,
                                            b(t[m], {
                                                width: `${s}px`,
                                                height: `${d}px`,
                                                position: "relative",
                                                "box-sizing": "border-box",
                                                overflow: "visible",
                                                visibility: "inherit"
                                            }),
                                            b(t[`${m}label`], {
                                                "line-height": l
                                            }),
                                            f(t[m], {
                                                "aria-hidden": !1
                                            })) : (b(t[m], {
                                                height: "0px",
                                                overflow: "hidden",
                                                position: "absolute",
                                                visibility: "hidden"
                                            }),
                                            f(t[m], {
                                                "aria-hidden": !0
                                            }),
                                            f(t[h], {
                                                tabIndex: -1
                                            }))
                                        }
                                        1 === a && (I(t[`${e}moreContainer`], {
                                            listposition: "lonely"
                                        }),
                                        I(t[c], {
                                            listposition: "lonely"
                                        }))
                                    }
                                    )(e, i, t, c)
                                }
                            }
                        }
                        ;
                        const G = "wix-dropdown-menu"
                          , F = (e=globalThis.window) => {
                            if (e && void 0 === e.customElements.get(G)) {
                                const t = h()
                                  , i = function(e, t, i=window) {
                                    const n = x(i);
                                    return class extends e {
                                        constructor() {
                                            super(...arguments),
                                            this._visible = !1,
                                            this._mutationIds = {
                                                read: null,
                                                write: null
                                            },
                                            this._itemsContainer = null,
                                            this._dropContainer = null,
                                            this._labelItems = []
                                        }
                                        static get observedAttributes() {
                                            return ["data-hovered-item"]
                                        }
                                        attributeChangedCallback() {
                                            this._isVisible() && this.reLayout()
                                        }
                                        connectedCallback() {
                                            this._id = this.getAttribute("id"),
                                            this._hideElement(),
                                            this._waitForDomLoad().then(( () => {
                                                super.observeResize(),
                                                this._observeChildrenResize(),
                                                this.reLayout()
                                            }
                                            ))
                                        }
                                        disconnectedCallback() {
                                            t.mutationService.clear(this._mutationIds.read),
                                            t.mutationService.clear(this._mutationIds.write),
                                            super.disconnectedCallback()
                                        }
                                        _waitForDomLoad() {
                                            let e;
                                            const t = new Promise((t => {
                                                e = t
                                            }
                                            ));
                                            return this._isDomReady() ? e() : (this._waitForDomReadyObserver = new i.MutationObserver(( () => this._onRootMutate(e))),
                                            this._waitForDomReadyObserver.observe(this, {
                                                childList: !0,
                                                subtree: !0
                                            })),
                                            t
                                        }
                                        _isDomReady() {
                                            return this._itemsContainer = this.getRootNode().getElementById(`${this._id}itemsContainer`),
                                            this._dropContainer = this.getRootNode().getElementById(`${this._id}dropWrapper`),
                                            this._itemsContainer && this._dropContainer
                                        }
                                        _onRootMutate(e) {
                                            this._isDomReady() && (this._waitForDomReadyObserver.disconnect(),
                                            e())
                                        }
                                        _observeChildrenResize() {
                                            const e = Array.from(this._itemsContainer.childNodes);
                                            this._labelItems = e.map((e => this.getRootNode().getElementById(`${e.getAttribute("id")}label`))),
                                            this._labelItems.forEach((e => super.observeChildResize(e)))
                                        }
                                        _setVisibility(e) {
                                            this._visible = e,
                                            this.style.visibility = e ? "inherit" : "hidden"
                                        }
                                        _isVisible() {
                                            return this._visible
                                        }
                                        _hideElement() {
                                            this._setVisibility(!1)
                                        }
                                        _showElement() {
                                            this._setVisibility(!0)
                                        }
                                        reLayout() {
                                            let e, i;
                                            t.mutationService.clear(this._mutationIds.read),
                                            t.mutationService.clear(this._mutationIds.write),
                                            this._mutationIds.read = t.mutationService.measure(( () => {
                                                const t = n.measure(this._id, this);
                                                e = t.measures,
                                                i = t.domNodes
                                            }
                                            )),
                                            this._mutationIds.write = t.mutationService.mutate(( () => {
                                                n.patch(this._id, e, i),
                                                this._showElement()
                                            }
                                            ))
                                        }
                                    }
                                }(O(e), {
                                    resizeService: t,
                                    mutationService: r()
                                }, e);
                                e.customElements.define(G, i)
                            }
                        }
                        ;
                        const N = "wix-iframe"
                          , P = (e=globalThis.window) => {
                            if (e && void 0 === e.customElements.get(N)) {
                                const t = function(e) {
                                    return class extends e {
                                        constructor() {
                                            super()
                                        }
                                        reLayout() {
                                            const e = this.querySelector("iframe");
                                            if (e) {
                                                const t = e.dataset.src;
                                                t && e.src !== t && (e.src = t,
                                                e.dataset.src = "",
                                                this.dataset.src = "")
                                            }
                                        }
                                        attributeChangedCallback(e, t, i) {
                                            i && this.reLayout()
                                        }
                                        static get observedAttributes() {
                                            return ["data-src"]
                                        }
                                    }
                                }(O(e));
                                v(e, N, t)
                            }
                        }
                          , k = {
                            measure(e, t, {hasBgScrollEffect: i, videoWidth: n, videoHeight: r, fittingType: o, alignType: s="center", qualities: a, staticVideoUrl: c, videoId: h, videoFormat: l, focalPoint: m}) {
                                const g = i ? t.offsetWidth : e.parentElement.offsetWidth
                                  , p = e.parentElement.offsetHeight
                                  , f = parseInt(n, 10)
                                  , b = parseInt(r, 10)
                                  , _ = function(e, t, i, n) {
                                    return {
                                        wScale: e / i,
                                        hScale: t / n
                                    }
                                }(g, p, f, b)
                                  , T = function(e, t, i, n) {
                                    let r;
                                    r = e === u.fittingTypes.SCALE_TO_FIT ? Math.min(t.wScale, t.hScale) : Math.max(t.wScale, t.hScale);
                                    return {
                                        width: Math.round(i * r),
                                        height: Math.round(n * r)
                                    }
                                }(o, _, f, b)
                                  , I = function(e, {width: t, height: i}) {
                                    const n = ( (e, t) => {
                                        const i = e.reduce(( (e, i) => (e[t(i)] = i,
                                        e)), {});
                                        return Object.values(i)
                                    }
                                    )(e, (e => e.size))
                                      , r = n.find((e => e.size > t * i));
                                    return r || e[e.length - 1]
                                }(a, T)
                                  , E = function(e, t, i, n) {
                                    if ("mp4" === n)
                                        return e.url ? d(t, e.url) : d(t, i, e.quality, n, "file.mp4");
                                    return ""
                                }(I, c, h, l)
                                  , w = function(e, t) {
                                    const i = e.networkState === e.NETWORK_NO_SOURCE
                                      , n = !e.currentSrc.endsWith(t);
                                    return t && (n || i)
                                }(e, E)
                                  , v = L[o] || "cover"
                                  , A = m ? function(e, t, i) {
                                    const {width: n, height: r} = e
                                      , {width: o, height: s} = t
                                      , {x: a, y: c} = i;
                                    if (!o || !s)
                                        return `${a}% ${c}%`;
                                    const h = Math.max(o / n, s / r)
                                      , l = n * h
                                      , d = r * h
                                      , u = Math.max(0, Math.min(l - o, l * (a / 100) - o / 2))
                                      , m = Math.max(0, Math.min(d - s, d * (c / 100) - s / 2))
                                      , g = u && Math.floor(u / (l - o) * 100)
                                      , p = m && Math.floor(m / (d - s) * 100);
                                    return `${g}% ${p}%`
                                }(T, {
                                    width: g,
                                    height: p
                                }, m) : ""
                                  , O = s.replace("_", " ");
                                return {
                                    videoSourceUrl: E,
                                    needsSrcUpdate: w,
                                    videoStyle: {
                                        height: "100%",
                                        width: "100%",
                                        objectFit: v,
                                        objectPosition: A || O
                                    }
                                }
                            },
                            mutate(e, t, i, n, r, o, s, a, c, h, l) {
                                r ? i.setAttribute("autoplay", "") : i.removeAttribute("autoplay"),
                                t ? b(t, n) : (!function(e, t, i, n, r, o) {
                                    o && t.paused && (i.style.opacity = "1",
                                    t.style.opacity = "0");
                                    const s = t.paused || "" === t.currentSrc
                                      , a = e || o;
                                    if (a && s)
                                        if (t.ontimeupdate = null,
                                        t.onseeked = null,
                                        t.onplay = null,
                                        !o && r) {
                                            const e = t.muted;
                                            t.muted = !0,
                                            t.ontimeupdate = () => {
                                                t.currentTime > 0 && (t.ontimeupdate = null,
                                                t.onseeked = () => {
                                                    t.onseeked = null,
                                                    t.muted = e,
                                                    B(t, i, n)
                                                }
                                                ,
                                                t.currentTime = 0)
                                            }
                                        } else
                                            t.onplay = () => {
                                                o || (t.onplay = null),
                                                B(t, i, n)
                                            }
                                }(s, i, e, a, r, l),
                                b(i, n)),
                                function(e, t, i) {
                                    e && (t.src = i,
                                    t.load())
                                }(s, i, o),
                                i.playbackRate = h
                            }
                        };
                        function B(e, t, i) {
                            "fade" === i && (t.style.transition = "opacity 1.6s ease-out"),
                            t.style.opacity = "0",
                            e.style.opacity = "1"
                        }
                        function H(e, t, i) {
                            return class extends e {
                                constructor() {
                                    super()
                                }
                                connectedCallback() {
                                    t.isExperimentOpen("specs.thunderbolt.videoLazyLoading") ? i.disableImagesLazyLoading ? this.reLayout() : t.intersectionObserver.observe(this) : super.connectedCallback.call(this)
                                }
                                disconnectedCallback() {
                                    t.isExperimentOpen("specs.thunderbolt.videoLazyLoading") ? (this.unobserveResize(),
                                    this.unobserveIntersect(),
                                    this.unobserveChildren()) : super.disconnectedCallback.call(this)
                                }
                                unobserveIntersect() {
                                    t.intersectionObserver?.unobserve(this)
                                }
                                reLayout() {
                                    const {isVideoDataExists: e, videoWidth: n, videoHeight: r, qualities: o, videoId: s, videoFormat: a, alignType: c, fittingType: h, focalPoint: l, hasBgScrollEffect: d, autoPlay: u, animatePoster: m, containerId: g, isEditorMode: p, playbackRate: f, hasAlpha: b} = JSON.parse(this.dataset.videoInfo);
                                    if (!e)
                                        return;
                                    const _ = !i.prefersReducedMotion && u
                                      , T = this.querySelector(`video[id^="${g}"]`)
                                      , I = this.querySelector(`.bgVideoposter[id^="${g}"]`);
                                    if (this.unobserveChildren(),
                                    !T || !I)
                                        return void this.observeChildren(this);
                                    const E = this.getRootNode().getElementById(`${g}`)
                                      , L = E.querySelector(`.webglcanvas[id^="${g}"]`);
                                    !(b || "true" === E.dataset.hasAlpha) || L ? t.mutationService.measure(( () => {
                                        const e = k.measure(T, E, {
                                            hasBgScrollEffect: d,
                                            videoWidth: n,
                                            videoHeight: r,
                                            fittingType: h,
                                            alignType: c,
                                            qualities: o,
                                            staticVideoUrl: i.staticVideoUrl,
                                            videoId: s,
                                            videoFormat: a,
                                            focalPoint: l
                                        })
                                          , {videoSourceUrl: u, needsSrcUpdate: g, videoStyle: b} = e;
                                        t.mutationService.mutate(( () => {
                                            k.mutate(I, L, T, b, _, u, g, m, a, f, p)
                                        }
                                        ))
                                    }
                                    )) : requestAnimationFrame(( () => this.reLayout()))
                                }
                                attributeChangedCallback(e, t) {
                                    t && this.reLayout()
                                }
                                static get observedAttributes() {
                                    return ["data-video-info"]
                                }
                            }
                        }
                        const $ = "wix-video"
                          , U = (e=globalThis.window, t, i={
                            experiments: {}
                        }) => {
                            if (e && void 0 === e.customElements.get($)) {
                                const n = O(e);
                                let r;
                                if (t?.isExperimentOpen("specs.thunderbolt.videoLazyLoading")) {
                                    const e = new IntersectionObserver((e => e.map((e => {
                                        if (e.isIntersecting) {
                                            const t = e.target;
                                            t.unobserveIntersect(),
                                            t.observeResize()
                                        }
                                        return e
                                    }
                                    ))),{
                                        rootMargin: "50% 100%"
                                    });
                                    r = H(n, {
                                        ...t,
                                        intersectionObserver: e
                                    }, i)
                                } else
                                    r = H(n, t, i);
                                v(e, $, r)
                            }
                        }
                    }
                    ,
                    96567: (e, t, i) => {
                        var n = i(17709)
                          , r = i.n(n)
                          , o = i(33842)
                          , s = i(22538)
                          , a = i(30012);
                        const c = {
                            imageClientApi: s,
                            ...{
                                init: function(e, t=window) {
                                    !/**
 * @license
 * Copyright (c) 2016 The Polymer Project Authors. All rights reserved.
 * This code may only be used under the BSD style license found at http://polymer.github.io/LICENSE.txt
 * The complete set of authors may be found at http://polymer.github.io/AUTHORS.txt
 * The complete set of contributors may be found at http://polymer.github.io/CONTRIBUTORS.txt
 * Code distributed by Google as part of the polymer project is also
 * subject to an additional IP rights grant found at http://polymer.github.io/PATENTS.txt
 */
                                    function(e) {
                                        if (void 0 === e.Reflect || void 0 === e.customElements || e.customElements.hasOwnProperty("polyfillWrapFlushCallback"))
                                            return;
                                        const t = e.HTMLElement;
                                        e.HTMLElement = function() {
                                            return e.Reflect.construct(t, [], this.constructor)
                                        }
                                        ,
                                        e.HTMLElement.prototype = t.prototype,
                                        e.HTMLElement.prototype.constructor = e.HTMLElement,
                                        e.Object.setPrototypeOf(e.HTMLElement, t),
                                        e.Object.defineProperty(e.HTMLElement, "name", {
                                            value: t.name
                                        })
                                    }(t);
                                    const i = {
                                        registry: new Set,
                                        observe(e) {
                                            i.registry.add(e)
                                        },
                                        unobserve(e) {
                                            i.registry.delete(e)
                                        }
                                    };
                                    e.windowResizeService.init((0,
                                    a.vk)(( () => i.registry.forEach((e => e.reLayout())))), t);
                                    const n = (0,
                                    a.Aq)()
                                      , r = (e, i) => {
                                        void 0 === t.customElements.get(e) && t.customElements.define(e, i)
                                    }
                                      , o = (0,
                                    a.yO)({
                                        resizeService: n
                                    }, t);
                                    return t.customElementNamespace = {
                                        WixElement: o
                                    },
                                    r("wix-element", o),
                                    {
                                        contextWindow: t,
                                        defineWixBgMedia: e => {
                                            const n = (0,
                                            a.NL)(o, {
                                                windowResizeService: i,
                                                ...e
                                            }, t);
                                            r("wix-bg-media", n)
                                        }
                                        ,
                                        defineMultiColumnRepeaterElement: () => {
                                            const e = (0,
                                            a._o)();
                                            r(a.KU, e)
                                        }
                                    }
                                }
                            }
                        };
                        var h = i(3412);
                        const l = () => ({
                            getSiteScale: () => {
                                const e = document.querySelector("#site-root");
                                return e ? e.getBoundingClientRect().width / e.offsetWidth : 1
                            }
                        })
                          , d = () => {
                            const e = {
                                init: e => new ResizeObserver(e)
                            }
                              , t = {
                                init: e => window.addEventListener("resize", e)
                            }
                              , i = l();
                            return c.init({
                                resizeService: e,
                                windowResizeService: t,
                                siteService: i
                            })
                        }
                          , u = (e, t, i, n) => {
                            const {getMediaDimensions: r, ...s} = o[e] || {};
                            return r ? {
                                ...r(t, i, n),
                                ...s
                            } : {
                                width: t,
                                height: i,
                                ...s
                            }
                        }
                          , {experiments: m, media: g, requestUrl: p} = window.viewerModel;
                        ( (e, t, i, n) => {
                            const {environmentConsts: o, wixCustomElements: s, media: a, requestUrl: m, mediaServices: g} = ( (e, t, i, n) => {
                                const o = {
                                    staticMediaUrl: e.media.staticMediaUrl,
                                    mediaRootUrl: e.media.mediaRootUrl,
                                    experiments: {},
                                    isViewerMode: !0,
                                    devicePixelRatio: /iemobile/i.test(navigator.userAgent) ? Math.round(window.screen.availWidth / (window.screen.width || window.document.documentElement.clientWidth)) : window.devicePixelRatio,
                                    ...n
                                }
                                  , s = {
                                    mutationService: r(),
                                    isExperimentOpen: t => Boolean(e.experiments[t]),
                                    siteService: l()
                                }
                                  , a = {
                                    getMediaDimensionsByEffect: u,
                                    ...s,
                                    ...i
                                };
                                return {
                                    ...e,
                                    wixCustomElements: t || d(),
                                    services: s,
                                    environmentConsts: o,
                                    mediaServices: a
                                }
                            }
                            )(e, t, i, n)
                              , p = s?.contextWindow || window;
                            p.wixCustomElements = s,
                            Object.assign(p.customElementNamespace, {
                                mediaServices: g,
                                environmentConsts: o,
                                requestUrl: m,
                                staticVideoUrl: a.staticVideoUrl
                            }),
                            (0,
                            h.g)({
                                ...g
                            }, s.contextWindow, o),
                            s.defineWixBgMedia(g),
                            s.defineMultiColumnRepeaterElement(),
                            window.__imageClientApi__ = c.imageClientApi
                        }
                        )({
                            experiments: m,
                            media: g,
                            requestUrl: p
                        })
                    }
                }]);
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/custom-element-utils.inline.6c144675.bundle.min.js.map
            </script>
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/initCustomElements.inline.d403acd5.bundle.min.js">
                "use strict";
                (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[6916], {
                    33842: (e, t, i) => {
                        i.r(t),
                        i.d(t, {
                            BackgroundParallax: () => o,
                            BackgroundParallaxZoom: () => r,
                            BackgroundReveal: () => c,
                            BgCloseUp: () => d,
                            BgExpand: () => h,
                            BgFabeBack: () => l,
                            BgFadeIn: () => g,
                            BgFadeOut: () => u,
                            BgFake3D: () => m,
                            BgPanLeft: () => f,
                            BgPanRight: () => b,
                            BgParallax: () => p,
                            BgPullBack: () => v,
                            BgReveal: () => M,
                            BgRotate: () => w,
                            BgShrink: () => y,
                            BgSkew: () => x,
                            BgUnwind: () => D,
                            BgZoomIn: () => I,
                            BgZoomOut: () => S,
                            ImageParallax: () => E,
                            ImageReveal: () => P
                        });
                        var s = i(41217);
                        const n = (e, t) => ({
                            width: e,
                            height: t
                        })
                          , a = (e, t, i) => ({
                            width: e,
                            height: Math.max(t, i)
                        });
                        const o = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , r = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , c = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , d = {
                            getMediaDimensions: n
                        }
                          , h = {
                            getMediaDimensions: n
                        }
                          , l = {
                            getMediaDimensions: n
                        }
                          , g = {
                            getMediaDimensions: n
                        }
                          , u = {
                            getMediaDimensions: n
                        }
                          , m = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , f = {
                            getMediaDimensions: (e, t) => ({
                                width: 1.2 * e,
                                height: t
                            })
                        }
                          , b = {
                            getMediaDimensions: (e, t) => ({
                                width: 1.2 * e,
                                height: t
                            })
                        }
                          , p = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , v = {
                            getMediaDimensions: n
                        }
                          , M = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , w = {
                            getMediaDimensions: (e, t) => function(e, t, i) {
                                const n = (0,
                                s.kU)(i)
                                  , a = Math.hypot(e, t) / 2
                                  , o = Math.acos(e / 2 / a)
                                  , r = e * Math.abs(Math.cos(n)) + t * Math.abs(Math.sin(n))
                                  , c = e * Math.abs(Math.sin(n)) + t * Math.abs(Math.cos(n));
                                return {
                                    width: Math.ceil(n < o ? r : 2 * a),
                                    height: Math.ceil(n < (0,
                                    s.kU)(90) - o ? c : 2 * a)
                                }
                            }(e, t, 22)
                        }
                          , y = {
                            getMediaDimensions: n
                        }
                          , x = {
                            getMediaDimensions: (e, t) => function(e, t, i) {
                                const n = (0,
                                s.kU)(i);
                                return {
                                    width: e,
                                    height: e * Math.tan(n) + t
                                }
                            }(e, t, 20)
                        }
                          , D = {
                            getMediaDimensions: n
                        }
                          , I = {
                            hasParallax: !0,
                            getMediaDimensions: a
                        }
                          , S = {
                            getMediaDimensions: (e, t) => ({
                                width: 1.15 * e,
                                height: 1.15 * t
                            })
                        }
                          , E = {
                            getMediaDimensions: (e, t) => ({
                                width: e,
                                height: 1.5 * t
                            })
                        }
                          , P = {
                            getMediaDimensions: (e, t, i) => ({
                                width: e,
                                height: i
                            })
                        }
                    }
                    ,
                    3412: (e, t, i) => {
                        i.d(t, {
                            g: () => w
                        });
                        var s = i(22538);
                        const n = {
                            columnCount: 1,
                            columns: 1,
                            fontWeight: 1,
                            lineHeight: 1,
                            opacity: 1,
                            zIndex: 1,
                            zoom: 1
                        }
                          , a = (e, t) => (Array.isArray(t) ? t : [t]).reduce(( (t, i) => {
                            const s = e[i];
                            return void 0 !== s ? Object.assign(t, {
                                [i]: s
                            }) : t
                        }
                        ), {})
                          , o = (e, t) => e && t && Object.keys(t).forEach((i => {
                            const s = i
                              , a = t[s];
                            void 0 !== a ? e.style[s] = ( (e, t) => "number" != typeof t || n[e] ? t.toString() : `${t}px`)(s, a) : e.style.removeProperty(s)
                        }
                        ))
                          , r = (e, t, i) => {
                            if (!e.targetWidth || !e.targetHeight || !e.imageData.uri)
                                return {
                                    uri: "",
                                    css: {},
                                    transformed: !1
                                };
                            const {imageData: n} = e
                              , o = e.displayMode || s.fittingTypes.SCALE_TO_FILL
                              , r = Object.assign(a(n, ["upscaleMethod"]), a(e, ["filters", "encoding"]), e.quality || n.quality, {
                                hasAnimation: e?.hasAnimation || n?.hasAnimation
                            })
                              , h = e.imageData.devicePixelRatio || t.devicePixelRatio
                              , l = d(h)
                              , g = Object.assign(a(n, ["width", "height", "crop", "name", "focalPoint"]), {
                                id: n.uri
                            })
                              , u = {
                                width: e.targetWidth,
                                height: e.targetHeight,
                                htmlTag: i || "img",
                                pixelAspectRatio: l,
                                alignment: e.alignType || s.alignTypes.CENTER
                            }
                              , m = (0,
                            s.getData)(o, g, u, r);
                            return m.uri = c(m.uri, t.staticMediaUrl, t.mediaRootUrl),
                            m
                        }
                          , c = (e, t, i) => {
                            if (/(^https?)|(^data)|(^blob)|(^\/\/)/.test(e))
                                return e;
                            let s = `${t}/`;
                            return e && (/^micons\//.test(e) ? s = i : "ico" === /[^.]+$/.exec(e)?.[0] && (s = s.replace("media", "ficons"))),
                            s + e
                        }
                          , d = e => {
                            const t = window.location.search.split("&").map((e => e.split("="))).find((e => e[0]?.toLowerCase().includes("devicepixelratio")));
                            return (t?.[1] ? Number(t[1]) : null) || e || 1
                        }
                          , h = e => e.getAttribute("src")
                          , l = 80;
                        const g = {
                            measure: function(e, t, i, {containerElm: s, bgEffect: n="none", sourceSets: a}, o) {
                                const r = i.image
                                  , c = i[e]
                                  , d = (g = o.getScreenHeightOverride?.(),
                                g || document.documentElement.clientHeight || window.innerHeight || 0);
                                var g;
                                const u = s?.dataset.mediaHeightOverrideType
                                  , m = n && "none" !== n || a && a.some((e => e.scrollEffect))
                                  , f = s && m ? s : c
                                  , b = window.getComputedStyle(c).getPropertyValue("--bg-scrub-effect")
                                  , {width: p, height: v} = o.getMediaDimensionsByEffect?.(b || n, f.offsetWidth, f.offsetHeight, d) || {
                                    width: c.offsetWidth,
                                    height: c.offsetHeight
                                };
                                if (a && (t.sourceSetsTargetHeights = function(e, t, i, s, n) {
                                    const a = {};
                                    return e.forEach(( ({mediaQuery: e, scrollEffect: o}) => {
                                        a[e] = n.getMediaDimensionsByEffect(o, t, i, s).height
                                    }
                                    )),
                                    a
                                }(a, f.offsetWidth, f.offsetHeight, d, o)),
                                !r)
                                    return;
                                const M = h(r);
                                b && (t.top = .5 * (c.offsetHeight - v),
                                t.left = .5 * (c.offsetWidth - p)),
                                t.width = p,
                                t.height = function(e, t) {
                                    return "fixed" === t || "viewport" === t ? document.documentElement.clientHeight + l : e
                                }(v, u),
                                t.screenHeight = d,
                                t.imgSrc = M,
                                t.boundingRect = c.getBoundingClientRect(),
                                t.mediaHeightOverrideType = u,
                                t.srcset = r.srcset
                            },
                            patch: function(e, t, i, n, a, c, d, h, l) {
                                if (!Object.keys(t).length)
                                    return;
                                const {imageData: g} = n
                                  , u = i[e]
                                  , m = i.image;
                                h && (g.devicePixelRatio = 1);
                                const f = n.targetScale || 1
                                  , b = {
                                    ...n,
                                    ...!n.skipMeasure && {
                                        targetWidth: (t.width || 0) * f,
                                        targetHeight: (t.height || 0) * f
                                    },
                                    displayMode: g.displayMode
                                }
                                  , p = r(b, a, "img")
                                  , v = p?.css?.img || {}
                                  , M = function(e, t, i, s, n) {
                                    const a = function(e, t=1) {
                                        return 1 !== t ? {
                                            ...e,
                                            width: "100%",
                                            height: "100%"
                                        } : e
                                    }(t, s);
                                    if (n && (delete a.height,
                                    a.width = "100%"),
                                    !e)
                                        return a;
                                    const o = {
                                        ...a
                                    };
                                    return "fill" === i ? (o.position = "absolute",
                                    o.top = "0") : "fit" === i && (o.height = "100%"),
                                    "fixed" === e && (o["will-change"] = "transform"),
                                    o.objectPosition && (o.objectPosition = t.objectPosition.replace(/(center|bottom)$/, "top")),
                                    o
                                }(t.mediaHeightOverrideType, v, g.displayMode, f, d);
                                o(m, M),
                                (t.top || t.left) && o(u, {
                                    top: `${t.top}px`,
                                    left: `${t.left}px`
                                });
                                const w = p?.uri || ""
                                  , y = g?.hasAnimation || n?.hasAnimation
                                  , x = function(e, t, i) {
                                    const {sourceSets: s} = t;
                                    if (!s || !s.length)
                                        return;
                                    const n = {};
                                    return s.forEach(( ({mediaQuery: s, crop: a, focalPoint: o}) => {
                                        const c = {
                                            ...t,
                                            targetHeight: (e.sourceSetsTargetHeights || {})[s] || 0,
                                            imageData: {
                                                ...t.imageData,
                                                crop: a,
                                                focalPoint: o
                                            }
                                        }
                                          , d = r(c, i, "img");
                                        n[s] = d.uri || ""
                                    }
                                    )),
                                    n
                                }(t, b, a);
                                if (l && (m.dataset.ssrSrcDone = "true"),
                                n.isLQIP && n.lqipTransition && !("transitioned"in u.dataset) && (u.dataset.transitioned = "",
                                m.complete ? m.onload = function() {
                                    m.dataset.loadDone = ""
                                }
                                : m.onload = function() {
                                    m.complete ? m.dataset.loadDone = "" : m.onload = function() {
                                        m.dataset.loadDone = ""
                                    }
                                }
                                ),
                                c) {
                                    ( (e, t) => (0,
                                    s.getFileExtension)(e) === s.fileType.GIF || (0,
                                    s.getFileExtension)(e) === s.fileType.WEBP && t)(g.uri, y) ? (m.setAttribute("fetchpriority", "low"),
                                    m.setAttribute("loading", "lazy"),
                                    m.setAttribute("decoding", "async")) : m.setAttribute("fetchpriority", "high"),
                                    m.currentSrc !== w && m.setAttribute("src", w);
                                    t.srcset && !t.srcset.split(", ").some((e => e.split(" ")[0] === w)) && m.setAttribute("srcset", w),
                                    i.picture && b.sourceSets && Array.from(i.picture.querySelectorAll("source")).forEach((e => {
                                        const t = e.media || ""
                                          , i = x?.[t];
                                        e.srcset !== i && e.setAttribute("srcset", i || "")
                                    }
                                    ))
                                }
                            }
                        }
                          , u = {
                            parallax: "ImageParallax",
                            fixed: "ImageReveal"
                        };
                        const m = function(e, t, i) {
                            return class extends i.HTMLElement {
                                constructor() {
                                    super(),
                                    this.childListObserver = null,
                                    this.timeoutId = null
                                }
                                attributeChangedCallback(e, t) {
                                    t && this.reLayout()
                                }
                                connectedCallback() {
                                    t.disableImagesLazyLoading ? this.reLayout() : this.observeIntersect()
                                }
                                disconnectedCallback() {
                                    this.unobserveResize(),
                                    this.unobserveIntersect(),
                                    this.unobserveChildren()
                                }
                                static get observedAttributes() {
                                    return ["data-image-info"]
                                }
                                reLayout() {
                                    const s = {}
                                      , n = {}
                                      , a = this.getAttribute("id")
                                      , o = JSON.parse(this.dataset.imageInfo || "")
                                      , r = "true" === this.dataset.isResponsive
                                      , {bgEffectName: c} = this.dataset
                                      , {scrollEffect: d} = o.imageData
                                      , {sourceSets: l} = o
                                      , m = c || d && u[d];
                                    l && l.length && l.forEach((e => {
                                        e.scrollEffect && (e.scrollEffect = u[e.scrollEffect])
                                    }
                                    )),
                                    s[a] = this,
                                    o.containerId && (s[o.containerId] = i.document.getElementById(`${o.containerId}`));
                                    const f = o.containerId ? s[o.containerId] : void 0;
                                    if (s.image = this.querySelector("img"),
                                    s.picture = this.querySelector("picture"),
                                    !s.image) {
                                        const e = this;
                                        return void this.observeChildren(e)
                                    }
                                    this.unobserveChildren(),
                                    this.observeChildren(this),
                                    e.mutationService.measure(( () => {
                                        g.measure(a, n, s, {
                                            containerElm: f,
                                            bgEffect: m,
                                            sourceSets: l
                                        }, e)
                                    }
                                    ));
                                    const b = (i, c) => {
                                        e.mutationService.mutate(( () => {
                                            g.patch(a, n, s, o, t, i, r, m, c)
                                        }
                                        ))
                                    }
                                      , p = s.image
                                      , v = this.dataset.hasSsrSrc && !p.dataset.ssrSrcDone;
                                    !h(p) || v ? b(!0, !0) : this.debounceImageLoad(b)
                                }
                                debounceImageLoad(e) {
                                    clearTimeout(this.timeoutId),
                                    this.timeoutId = i.setTimeout(( () => {
                                        e(!0)
                                    }
                                    ), 250),
                                    e(!1)
                                }
                                observeResize() {
                                    e.resizeService?.observe(this)
                                }
                                unobserveResize() {
                                    e.resizeService?.unobserve(this)
                                }
                                observeIntersect() {
                                    e.intersectionService?.observe(this)
                                }
                                unobserveIntersect() {
                                    e.intersectionService?.unobserve(this)
                                }
                                observeChildren(e) {
                                    this.childListObserver || (this.childListObserver = new i.MutationObserver(( () => {
                                        this.reLayout()
                                    }
                                    ))),
                                    this.childListObserver.observe(e, {
                                        childList: !0
                                    })
                                }
                                unobserveChildren() {
                                    this.childListObserver && (this.childListObserver.disconnect(),
                                    this.childListObserver = null)
                                }
                            }
                        };
                        var f = i(17709)
                          , b = i.n(f);
                        const p = () => /iemobile/i.test(navigator.userAgent) ? Math.round(window.screen.availWidth / (window.screen.width || window.document.documentElement.clientWidth)) : window.devicePixelRatio
                          , v = "https://static.wixstatic.com/media"
                          , M = "https://static.wixstatic.com";
                        function w(e={}, t=null, i={}) {
                            if ("undefined" == typeof window)
                                return;
                            const s = {
                                staticMediaUrl: v,
                                mediaRootUrl: M,
                                experiments: {},
                                devicePixelRatio: p(),
                                ...i
                            }
                              , n = function(e, t) {
                                const i = "wow-image";
                                if (void 0 === (e = e || window).customElements.get(i)) {
                                    let s, n;
                                    return e.ResizeObserver && (s = new e.ResizeObserver((e => e.map((e => e.target.reLayout()))))),
                                    e.IntersectionObserver && (n = new IntersectionObserver((e => e.map((e => {
                                        if (e.isIntersecting) {
                                            const t = e.target;
                                            t.unobserveIntersect(),
                                            t.observeResize()
                                        }
                                        return e
                                    }
                                    ))),{
                                        rootMargin: "150% 100%"
                                    })),
                                    function(a) {
                                        const o = m({
                                            resizeService: s,
                                            intersectionService: n,
                                            mutationService: b(),
                                            ...t
                                        }, a, e);
                                        e.customElements.define(i, o)
                                    }
                                }
                            }(t, e);
                            n && n(s)
                        }
                    }
                    ,
                    41217: (e, t, i) => {
                        i.d(t, {
                            Io: () => n,
                            Rb: () => o,
                            _b: () => s,
                            kU: () => a
                        });
                        function s(e, t, i, s, n) {
                            return (n - e) * (s - i) / (t - e) + i
                        }
                        function n(e, t) {
                            let[i,s] = e
                              , [n,a] = t;
                            return Math.sqrt((n - i) ** 2 + (a - s) ** 2)
                        }
                        function a(e) {
                            return e * Math.PI / 180
                        }
                        function o(e, t, i) {
                            void 0 === e && (e = [0, 0]),
                            void 0 === t && (t = [0, 0]),
                            void 0 === i && (i = 0);
                            return (360 + i + 180 * Math.atan2(t[1] - e[1], t[0] - e[0]) / Math.PI) % 360
                        }
                    }
                }, e => {
                    e.O(0, [592, 8398], ( () => {
                        return t = 96567,
                        e(e.s = t);
                        var t
                    }
                    ));
                    e.O()
                }
                ]);
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/initCustomElements.inline.d403acd5.bundle.min.js.map
            </script>
            <!-- preloading pre-scripts -->
            <link href="https://siteassets.parastorage.com/pages/pages/thunderbolt?beckyExperiments=.DatePickerPortal%2C.LoginBarEnableLoggingInStateInSSR%2C.TextInputAutoFillFix%2C.buttonUdp%2C.calculateCollapsibleTextLineHeightByFont%2C.dataBindingInMasterResponsive%2C.dropAppsClientSpecMapByApplicationId%2C.fetchBlocksDevCenterWidgetIds%2C.fiveGridLineStudioSkins%2C.fixHasPinnedChildrenRepeaterCalc%2C.getSiteOverrideFromAllInflationChain%2C.imageEncodingAVIF%2C.invalidateDocumentData%2C.overflowXClipHeaderAndFooter%2C.overflowXClipInMobile%2C.prefetchPageResourcesVeloApi%2C.removeAllStatesBlocksFix%2C.shouldUseResponsiveImages%2C.sliderGalleryWAAPI%2C.updateRichTextSemanticClassNamesOnCorvid%2C.useInternalBlocksRefType%2C.useResponsiveImgClassicFixed%2C.useSvgLoaderFeature&blocksBuilderManifestGeneratorVersion=1.129.0&contentType=application%2Fjson&deviceType=Desktop&dfCk=6&dfVersion=1.4468.0&disableStaticPagesUrlHierarchy=false&editorName=Unknown&experiments=dm_bgScrubToMotionFixer%2Cdm_deleteLayoutOverridesForRefComponents%2Cdm_migrateOldHoverBoxToNewFixer%2Cdm_removeTpaChildren%2Cspecs.thunderbolt.use_data_fixed_pages_upstream&externalBaseUrl=https%3A%2F%2Faishtapamura.wixsite.com%2Fauthor&fileId=16abef83.bundle.min&formFactor=desktop&freemiumBanner=true&hasTPAWorkerOnSite=false&isHttps=true&isInSeo=false&isMultilingualEnabled=false&isTrackClicksAnalyticsEnabled=false&isUrlMigrated=true&isWixCodeOnPage=false&isWixCodeOnSite=false&language=en&languageResolutionMethod=QueryParam&metaSiteId=736c7394-4e87-4a3c-9265-7dad8dc29df5&module=thunderbolt-features&oneDocEnabled=true&originalLanguage=en&pageId=927f01_8304ca32f83b759906075e878bab5230_28.json&quickActionsMenuEnabled=false&registryLibrariesTopology=%5B%7B%22artifactId%22%3A%22editor-elements%22%2C%22namespace%22%3A%22wixui%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.13447.0%22%7D%2C%7B%22artifactId%22%3A%22editor-elements%22%2C%22namespace%22%3A%22dsgnsys%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.13447.0%22%7D%5D&remoteWidgetStructureBuilderVersion=1.251.0&siteId=2538b395-fb67-480b-aef2-fd071e6b62dd&siteRevision=28&staticHTMLComponentUrl=https%3A%2F%2Faishtapamura-wixsite-com.filesusr.com%2F&useSandboxInHTMLComp=true&viewMode=desktop" id="features_masterPage" as="fetch" position="post-scripts" rel="preload" crossorigin="anonymous"></link>
            <link href="https://siteassets.parastorage.com/pages/pages/thunderbolt?beckyExperiments=.DatePickerPortal%2C.LoginBarEnableLoggingInStateInSSR%2C.TextInputAutoFillFix%2C.buttonUdp%2C.calculateCollapsibleTextLineHeightByFont%2C.dataBindingInMasterResponsive%2C.dropAppsClientSpecMapByApplicationId%2C.fetchBlocksDevCenterWidgetIds%2C.fiveGridLineStudioSkins%2C.fixHasPinnedChildrenRepeaterCalc%2C.getSiteOverrideFromAllInflationChain%2C.imageEncodingAVIF%2C.invalidateDocumentData%2C.overflowXClipHeaderAndFooter%2C.overflowXClipInMobile%2C.prefetchPageResourcesVeloApi%2C.removeAllStatesBlocksFix%2C.shouldUseResponsiveImages%2C.sliderGalleryWAAPI%2C.updateRichTextSemanticClassNamesOnCorvid%2C.useInternalBlocksRefType%2C.useResponsiveImgClassicFixed%2C.useSvgLoaderFeature&blocksBuilderManifestGeneratorVersion=1.129.0&contentType=application%2Fjson&deviceType=Desktop&dfCk=6&dfVersion=1.4468.0&disableStaticPagesUrlHierarchy=false&editorName=Unknown&experiments=dm_bgScrubToMotionFixer%2Cdm_deleteLayoutOverridesForRefComponents%2Cdm_migrateOldHoverBoxToNewFixer%2Cdm_removeTpaChildren%2Cspecs.thunderbolt.use_data_fixed_pages_upstream&externalBaseUrl=https%3A%2F%2Faishtapamura.wixsite.com%2Fauthor&fileId=16abef83.bundle.min&formFactor=desktop&freemiumBanner=true&hasTPAWorkerOnSite=false&isHttps=true&isInSeo=false&isMultilingualEnabled=false&isTrackClicksAnalyticsEnabled=false&isUrlMigrated=true&isWixCodeOnPage=false&isWixCodeOnSite=false&language=en&languageResolutionMethod=QueryParam&metaSiteId=736c7394-4e87-4a3c-9265-7dad8dc29df5&module=thunderbolt-features&oneDocEnabled=true&originalLanguage=en&pageId=927f01_79b9b617722cbbb20fd8bc2410d724f3_28.json&quickActionsMenuEnabled=false&registryLibrariesTopology=%5B%7B%22artifactId%22%3A%22editor-elements%22%2C%22namespace%22%3A%22wixui%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.13447.0%22%7D%2C%7B%22artifactId%22%3A%22editor-elements%22%2C%22namespace%22%3A%22dsgnsys%22%2C%22url%22%3A%22https%3A%2F%2Fstatic.parastorage.com%2Fservices%2Feditor-elements%2F1.13447.0%22%7D%5D&remoteWidgetStructureBuilderVersion=1.251.0&siteId=2538b395-fb67-480b-aef2-fd071e6b62dd&siteRevision=28&staticHTMLComponentUrl=https%3A%2F%2Faishtapamura-wixsite-com.filesusr.com%2F&useSandboxInHTMLComp=true&viewMode=desktop" id="features_c1dmp" as="fetch" position="post-scripts" rel="preload" crossorigin="anonymous"></link>
            <!-- sentryOnLoad Setup Script -->
            <script id="sentryOnLoadSetup">
                function _extends() {
                    _extends = Object.assign || function(target) {
                        for (var i = 1; i < arguments.length; i++) {
                            var source = arguments[i];
                            for (var key in source) {
                                if (Object.prototype.hasOwnProperty.call(source, key)) {
                                    target[key] = source[key]
                                }
                            }
                        }
                        return target
                    }
                    ;
                    return _extends.apply(this, arguments)
                }
                (function() {
                    var SENTRY_REROUTED_MARK_KEY = "_REROUTED";
                    var SENTRY_IS_NON_WIX_TPA_MARK_KEY = "_isTPA";
                    var SENTRY_REROUTE_DATA_KEY = "_ROUTE_TO";
                    var addRerouteDataToSentryEvent = function(event) {
                        var _event_extra, _event_exception_values__stacktrace, _event_exception_values, _event_exception;
                        if (event == null ? void 0 : (_event_extra = event.extra) == null ? void 0 : _event_extra[SENTRY_REROUTE_DATA_KEY]) {
                            return
                        }
                        if (event == null ? void 0 : (_event_exception = event.exception) == null ? void 0 : (_event_exception_values = _event_exception.values) == null ? void 0 : (_event_exception_values__stacktrace = _event_exception_values[0].stacktrace) == null ? void 0 : _event_exception_values__stacktrace.frames) {
                            var frames = event.exception.values[0].stacktrace.frames;
                            var framesModuleMetadata = frames.filter(function(frame) {
                                return frame.module_metadata && frame.module_metadata.appId
                            }).map(function(v) {
                                return {
                                    appId: v.module_metadata.appId,
                                    release: v.module_metadata.release,
                                    dsn: v.module_metadata.dsn
                                }
                            });
                            var routeTo = framesModuleMetadata.slice(-1);
                            if (routeTo.length) {
                                var _window_wixEmbedsAPI, _app_monitoringComponent_monitoring, _app_monitoringComponent;
                                var appId = routeTo[0].appId;
                                var app = (_window_wixEmbedsAPI = window.wixEmbedsAPI) == null ? void 0 : _window_wixEmbedsAPI.getMonitoringConfig(appId);
                                if ((app == null ? void 0 : (_app_monitoringComponent = app.monitoringComponent) == null ? void 0 : (_app_monitoringComponent_monitoring = _app_monitoringComponent.monitoring) == null ? void 0 : _app_monitoringComponent_monitoring.type) === "SENTRY") {
                                    var _app_monitoringComponent_monitoring_sentryOptions, _app_monitoringComponent_monitoring1, _app_monitoringComponent1;
                                    var dsn = app == null ? void 0 : (_app_monitoringComponent1 = app.monitoringComponent) == null ? void 0 : (_app_monitoringComponent_monitoring1 = _app_monitoringComponent1.monitoring) == null ? void 0 : (_app_monitoringComponent_monitoring_sentryOptions = _app_monitoringComponent_monitoring1.sentryOptions) == null ? void 0 : _app_monitoringComponent_monitoring_sentryOptions.dsn;
                                    if (dsn) {
                                        if (!routeTo[0].dsn && dsn) {
                                            routeTo[0].dsn = dsn
                                        }
                                    }
                                }
                                if (app) {
                                    var _obj;
                                    event.extra = _extends({}, event.extra, (_obj = {},
                                    _obj[SENTRY_IS_NON_WIX_TPA_MARK_KEY] = !app.isWixTPA,
                                    _obj))
                                }
                                var _obj1;
                                event.extra = _extends({}, event.extra, (_obj1 = {},
                                _obj1[SENTRY_REROUTE_DATA_KEY] = routeTo,
                                _obj1[SENTRY_REROUTED_MARK_KEY] = true,
                                _obj1))
                            }
                        }
                    };
                    function overrideSentryInitOptions() {
                        var Sentry = window.Sentry;
                        var makeMultiplexedTransport = Sentry.makeMultiplexedTransport
                          , makeFetchTransport = Sentry.makeFetchTransport;
                        var transport = makeMultiplexedTransport ? makeMultiplexedTransport(makeFetchTransport, function(args) {
                            var event = args.getEvent();
                            if (event && event.extra && event.extra[SENTRY_REROUTE_DATA_KEY] && Array.isArray(event.extra[SENTRY_REROUTE_DATA_KEY])) {
                                return event.extra[SENTRY_REROUTE_DATA_KEY]
                            }
                            return []
                        }) : makeFetchTransport;
                        Sentry.init({
                            transport: transport,
                            integrations: [Sentry.browserTracingIntegration({
                                instrumentNavigation: false,
                                instrumentPageLoad: false
                            })],
                            tracePropagationTargets: [/^https:\/\/[a-zA-Z0-9-]+\.wix-app\.run\/.*/],
                            attachStacktrace: true,
                            beforeSend: function(event, hint) {
                                var customEvent = new CustomEvent("sentry-error",{
                                    cancelable: true,
                                    detail: {
                                        sentryEvent: event,
                                        sentryHint: hint
                                    }
                                });
                                var dispatchEventRes = window.dispatchEvent(customEvent);
                                if (!dispatchEventRes) {
                                    return null
                                }
                                if (event.extra) {
                                    if (event.extra[SENTRY_REROUTED_MARK_KEY]) {
                                        delete event.extra[SENTRY_REROUTED_MARK_KEY]
                                    }
                                    if (event.extra[SENTRY_IS_NON_WIX_TPA_MARK_KEY]) {
                                        delete event.extra[SENTRY_IS_NON_WIX_TPA_MARK_KEY]
                                    }
                                }
                                return event
                            }
                        });
                        if (Sentry.moduleMetadataIntegration) {
                            Sentry.addIntegration(Sentry.moduleMetadataIntegration());
                            Sentry.addGlobalEventProcessor(function(event) {
                                addRerouteDataToSentryEvent(event);
                                return event
                            })
                        }
                    }
                    window.sentryOnLoad = overrideSentryInitOptions
                }
                )();
            </script>
            <!-- Sentry Loader Script -->
            <script id="sentry">
                !function(n, e, r, t, o, i, a, c, s) {
                    for (var u = s, f = 0; f < document.scripts.length; f++)
                        if (document.scripts[f].src.indexOf(i) > -1) {
                            u && "no" === document.scripts[f].getAttribute("data-lazy") && (u = !1);
                            break
                        }
                    var p = [];
                    function l(n) {
                        return "e"in n
                    }
                    function d(n) {
                        return "p"in n
                    }
                    function _(n) {
                        return "f"in n
                    }
                    var v = [];
                    function y(n) {
                        u && (l(n) || d(n) || _(n) && n.f.indexOf("capture") > -1 || _(n) && n.f.indexOf("showReportDialog") > -1) && L(),
                        v.push(n)
                    }
                    function h() {
                        y({
                            e: [].slice.call(arguments)
                        })
                    }
                    function g(n) {
                        y({
                            p: n
                        })
                    }
                    function E() {
                        try {
                            n.SENTRY_SDK_SOURCE = "loader";
                            var e = n[o]
                              , i = e.init;
                            e.init = function(o) {
                                n.removeEventListener(r, h),
                                n.removeEventListener(t, g);
                                var a = c;
                                for (var s in o)
                                    Object.prototype.hasOwnProperty.call(o, s) && (a[s] = o[s]);
                                !function(n, e) {
                                    var r = n.integrations || [];
                                    if (!Array.isArray(r))
                                        return;
                                    var t = r.map((function(n) {
                                        return n.name
                                    }
                                    ));
                                    n.tracesSampleRate && -1 === t.indexOf("BrowserTracing") && (e.browserTracingIntegration ? r.push(e.browserTracingIntegration({
                                        enableInp: !0
                                    })) : e.BrowserTracing && r.push(new e.BrowserTracing));
                                    (n.replaysSessionSampleRate || n.replaysOnErrorSampleRate) && -1 === t.indexOf("Replay") && (e.replayIntegration ? r.push(e.replayIntegration()) : e.Replay && r.push(new e.Replay));
                                    n.integrations = r
                                }(a, e),
                                i(a)
                            }
                            ,
                            setTimeout((function() {
                                return function(e) {
                                    try {
                                        "function" == typeof n.sentryOnLoad && (n.sentryOnLoad(),
                                        n.sentryOnLoad = void 0)
                                    } catch (n) {
                                        console.error("Error while calling `sentryOnLoad` handler:"),
                                        console.error(n)
                                    }
                                    try {
                                        for (var r = 0; r < p.length; r++)
                                            "function" == typeof p[r] && p[r]();
                                        p.splice(0);
                                        for (r = 0; r < v.length; r++) {
                                            _(i = v[r]) && "init" === i.f && e.init.apply(e, i.a)
                                        }
                                        m() || e.init();
                                        var t = n.onerror
                                          , o = n.onunhandledrejection;
                                        for (r = 0; r < v.length; r++) {
                                            var i;
                                            if (_(i = v[r])) {
                                                if ("init" === i.f)
                                                    continue;
                                                e[i.f].apply(e, i.a)
                                            } else
                                                l(i) && t ? t.apply(n, i.e) : d(i) && o && o.apply(n, [i.p])
                                        }
                                    } catch (n) {
                                        console.error(n)
                                    }
                                }(e)
                            }
                            ))
                        } catch (n) {
                            console.error(n)
                        }
                    }
                    var O = !1;
                    function L() {
                        if (!O) {
                            O = !0;
                            var n = e.scripts[0]
                              , r = e.createElement("script");
                            r.src = a,
                            r.crossOrigin = "anonymous",
                            r.addEventListener("load", E, {
                                once: !0,
                                passive: !0
                            }),
                            n.parentNode.insertBefore(r, n)
                        }
                    }
                    function m() {
                        var e = n.__SENTRY__
                          , r = void 0 !== e && e.version;
                        return r ? !!e[r] : !(void 0 === e || !e.hub || !e.hub.getClient())
                    }
                    n[o] = n[o] || {},
                    n[o].onLoad = function(n) {
                        m() ? n() : p.push(n)
                    }
                    ,
                    n[o].forceLoad = function() {
                        setTimeout((function() {
                            L()
                        }
                        ))
                    }
                    ,
                    ["init", "addBreadcrumb", "captureMessage", "captureException", "captureEvent", "configureScope", "withScope", "showReportDialog"].forEach((function(e) {
                        n[o][e] = function() {
                            y({
                                f: e,
                                a: arguments
                            })
                        }
                    }
                    )),
                    n.addEventListener(r, h),
                    n.addEventListener(t, g),
                    u || setTimeout((function() {
                        L()
                    }
                    ))
                }(window, document, "error", "unhandledrejection", "Sentry", '605a7baede844d278b89dc95ae0a9123', 'https://browser.sentry-cdn.com/7.120.3/bundle.tracing.es5.min.js', {
                    "dsn": "https://605a7baede844d278b89dc95ae0a9123@sentry-next.wixpress.com/68",
                    "tracesSampleRate": 1
                }, true);
            </script>
            <!-- Sentry's makeMultiplexedTransport -->
            <script>
                !function(n) {
                    var r = {}
                      , t = function() {
                        return t = Object.assign || function(n) {
                            for (var r, t = 1, e = arguments.length; t < e; t++)
                                for (var o in r = arguments[t])
                                    Object.prototype.hasOwnProperty.call(r, o) && (n[o] = r[o]);
                            return n
                        }
                        ,
                        t.apply(this, arguments)
                    };
                    function e(n, r, t, e) {
                        return new (t || (t = Promise))((function(o, i) {
                            function u(n) {
                                try {
                                    f(e.next(n))
                                } catch (n) {
                                    i(n)
                                }
                            }
                            function c(n) {
                                try {
                                    f(e.throw(n))
                                } catch (n) {
                                    i(n)
                                }
                            }
                            function f(n) {
                                var r;
                                n.done ? o(n.value) : (r = n.value,
                                r instanceof t ? r : new t((function(n) {
                                    n(r)
                                }
                                ))).then(u, c)
                            }
                            f((e = e.apply(n, r || [])).next())
                        }
                        ))
                    }
                    function o(n, r) {
                        var t, e, o, i, u = {
                            label: 0,
                            sent: function() {
                                if (1 & o[0])
                                    throw o[1];
                                return o[1]
                            },
                            trys: [],
                            ops: []
                        };
                        return i = {
                            next: c(0),
                            throw: c(1),
                            return: c(2)
                        },
                        "function" == typeof Symbol && (i[Symbol.iterator] = function() {
                            return this
                        }
                        ),
                        i;
                        function c(c) {
                            return function(f) {
                                return function(c) {
                                    if (t)
                                        throw new TypeError("Generator is already executing.");
                                    for (; i && (i = 0,
                                    c[0] && (u = 0)),
                                    u; )
                                        try {
                                            if (t = 1,
                                            e && (o = 2 & c[0] ? e.return : c[0] ? e.throw || ((o = e.return) && o.call(e),
                                            0) : e.next) && !(o = o.call(e, c[1])).done)
                                                return o;
                                            switch (e = 0,
                                            o && (c = [2 & c[0], o.value]),
                                            c[0]) {
                                            case 0:
                                            case 1:
                                                o = c;
                                                break;
                                            case 4:
                                                return u.label++,
                                                {
                                                    value: c[1],
                                                    done: !1
                                                };
                                            case 5:
                                                u.label++,
                                                e = c[1],
                                                c = [0];
                                                continue;
                                            case 7:
                                                c = u.ops.pop(),
                                                u.trys.pop();
                                                continue;
                                            default:
                                                if (!(o = u.trys,
                                                (o = o.length > 0 && o[o.length - 1]) || 6 !== c[0] && 2 !== c[0])) {
                                                    u = 0;
                                                    continue
                                                }
                                                if (3 === c[0] && (!o || c[1] > o[0] && c[1] < o[3])) {
                                                    u.label = c[1];
                                                    break
                                                }
                                                if (6 === c[0] && u.label < o[1]) {
                                                    u.label = o[1],
                                                    o = c;
                                                    break
                                                }
                                                if (o && u.label < o[2]) {
                                                    u.label = o[2],
                                                    u.ops.push(c);
                                                    break
                                                }
                                                o[2] && u.ops.pop(),
                                                u.trys.pop();
                                                continue
                                            }
                                            c = r.call(n, u)
                                        } catch (n) {
                                            c = [6, n],
                                            e = 0
                                        } finally {
                                            t = o = 0
                                        }
                                    if (5 & c[0])
                                        throw c[1];
                                    return {
                                        value: c[0] ? c[1] : void 0,
                                        done: !0
                                    }
                                }([c, f])
                            }
                        }
                    }
                    function i(n) {
                        var r = "function" == typeof Symbol && Symbol.iterator
                          , t = r && n[r]
                          , e = 0;
                        if (t)
                            return t.call(n);
                        if (n && "number" == typeof n.length)
                            return {
                                next: function() {
                                    return n && e >= n.length && (n = void 0),
                                    {
                                        value: n && n[e++],
                                        done: !n
                                    }
                                }
                            };
                        throw new TypeError(r ? "Object is not iterable." : "Symbol.iterator is not defined.")
                    }
                    function u(n, r) {
                        var t = "function" == typeof Symbol && n[Symbol.iterator];
                        if (!t)
                            return n;
                        var e, o, i = t.call(n), u = [];
                        try {
                            for (; (void 0 === r || r-- > 0) && !(e = i.next()).done; )
                                u.push(e.value)
                        } catch (n) {
                            o = {
                                error: n
                            }
                        } finally {
                            try {
                                e && !e.done && (t = i.return) && t.call(i)
                            } finally {
                                if (o)
                                    throw o.error
                            }
                        }
                        return u
                    }
                    function c(n) {
                        return n && n.Math == Math ? n : void 0
                    }
                    var f = "object" == typeof globalThis && c(globalThis) || "object" == typeof window && c(window) || "object" == typeof self && c(self) || "object" == typeof global && c(global) || function() {
                        return this
                    }() || {}
                      , a = {};
                    var s = /^(?:(\w+):)\/\/(?:(\w+)(?::(\w+)?)?@)([\w.-]+)(?::(\d+))?\/(.+)/;
                    function v(n) {
                        var r = s.exec(n);
                        if (r) {
                            var t, e = u(r.slice(1), 6), o = e[0], i = e[1], c = e[2], v = void 0 === c ? "" : c, l = e[3], y = e[4], d = void 0 === y ? "" : y, p = "", h = e[5], b = h.split("/");
                            if (b.length > 1 && (p = b.slice(0, -1).join("/"),
                            h = b.pop()),
                            h) {
                                var w = h.match(/^\d+/);
                                w && (h = w[0])
                            }
                            return {
                                protocol: (t = {
                                    host: l,
                                    pass: v,
                                    path: p,
                                    projectId: h,
                                    port: d,
                                    protocol: o,
                                    publicKey: i
                                }).protocol,
                                publicKey: t.publicKey || "",
                                pass: t.pass || "",
                                host: t.host,
                                port: t.port || "",
                                path: t.path || "",
                                projectId: t.projectId
                            }
                        }
                        !function(n) {
                            if (!("console"in f))
                                return n();
                            var r = f.console
                              , t = {}
                              , e = Object.keys(a);
                            e.forEach((function(n) {
                                var e = a[n];
                                t[n] = r[n],
                                r[n] = e
                            }
                            ));
                            try {
                                n()
                            } finally {
                                e.forEach((function(n) {
                                    r[n] = t[n]
                                }
                                ))
                            }
                        }((function() {
                            console.error("Invalid Sentry Dsn: ".concat(n))
                        }
                        ))
                    }
                    function l(n, r) {
                        return e = t({
                            sentry_key: n.publicKey,
                            sentry_version: "7"
                        }, r && {
                            sentry_client: "".concat(r.name, "/").concat(r.version)
                        }),
                        Object.keys(e).map((function(n) {
                            return "".concat(encodeURIComponent(n), "=").concat(encodeURIComponent(e[n]))
                        }
                        )).join("&");
                        var e
                    }
                    function y(n, r) {
                        var t;
                        return function(n, r) {
                            var t, e, o = n[1];
                            try {
                                for (var u = i(o), c = u.next(); !c.done; c = u.next()) {
                                    var f = c.value;
                                    if (r(f, f[0].type))
                                        return !0
                                }
                            } catch (n) {
                                t = {
                                    error: n
                                }
                            } finally {
                                try {
                                    c && !c.done && (e = u.return) && e.call(u)
                                } finally {
                                    if (t)
                                        throw t.error
                                }
                            }
                        }(n, (function(n, e) {
                            return r.includes(e) && (t = Array.isArray(n) ? n[1] : void 0),
                            !!t
                        }
                        )),
                        t
                    }
                    for (var d in r.makeMultiplexedTransport = function(n, r) {
                        return function(c) {
                            var f = n(c)
                              , a = new Map;
                            function s(r, i) {
                                var u = i ? "".concat(r, ":").concat(i) : r
                                  , f = a.get(u);
                                if (!f) {
                                    var s = v(r);
                                    if (!s)
                                        return;
                                    var d = function(n, r) {
                                        void 0 === r && (r = {});
                                        var t = "string" == typeof r ? r : r.tunnel
                                          , e = "string" != typeof r && r.t ? r.t.sdk : void 0;
                                        return t || "".concat(function(n) {
                                            return "".concat(function(n) {
                                                var r = n.protocol ? "".concat(n.protocol, ":") : ""
                                                  , t = n.port ? ":".concat(n.port) : "";
                                                return "".concat(r, "//").concat(n.host).concat(t).concat(n.path ? "/".concat(n.path) : "", "/api/")
                                            }(n)).concat(n.projectId, "/envelope/")
                                        }(n), "?").concat(l(n, e))
                                    }(s, c.tunnel);
                                    f = i ? function(n, r) {
                                        var i = this;
                                        return function(u) {
                                            var c = n(u);
                                            return t(t({}, c), {
                                                send: function(n) {
                                                    return e(i, void 0, void 0, (function() {
                                                        var t;
                                                        return o(this, (function(e) {
                                                            return (t = y(n, ["event", "transaction", "profile", "replay_event"])) && (t.release = r),
                                                            [2, c.send(n)]
                                                        }
                                                        ))
                                                    }
                                                    ))
                                                }
                                            })
                                        }
                                    }(n, i)(t(t({}, c), {
                                        url: d
                                    })) : n(t(t({}, c), {
                                        url: d
                                    })),
                                    a.set(u, f)
                                }
                                return [r, f]
                            }
                            return {
                                send: function(n) {
                                    return e(this, void 0, void 0, (function() {
                                        function e(r) {
                                            var t = r && r.length ? r : ["event"];
                                            return y(n, t)
                                        }
                                        var i;
                                        return o(this, (function(o) {
                                            switch (o.label) {
                                            case 0:
                                                return 0 === (i = r({
                                                    envelope: n,
                                                    getEvent: e
                                                }).map((function(n) {
                                                    return "string" == typeof n ? s(n, void 0) : s(n.dsn, n.release)
                                                }
                                                )).filter((function(n) {
                                                    return !!n
                                                }
                                                ))).length && i.push(["", f]),
                                                [4, Promise.all(i.map((function(r) {
                                                    var e = u(r, 2)
                                                      , o = e[0];
                                                    return e[1].send(function(n, r) {
                                                        return e = r ? t(t({}, n[0]), {
                                                            dsn: r
                                                        }) : n[0],
                                                        void 0 === (o = n[1]) && (o = []),
                                                        [e, o];
                                                        var e, o
                                                    }(n, o))
                                                }
                                                )))];
                                            case 1:
                                                return [2, o.sent()[0]]
                                            }
                                        }
                                        ))
                                    }
                                    ))
                                },
                                flush: function(n) {
                                    return e(this, void 0, void 0, (function() {
                                        var r, t, e, c, s, v, l, y, d, p;
                                        return o(this, (function(o) {
                                            switch (o.label) {
                                            case 0:
                                                return [4, f.flush(n)];
                                            case 1:
                                                r = [o.sent()],
                                                o.label = 2;
                                            case 2:
                                                o.trys.push([2, 7, 8, 9]),
                                                t = i(a),
                                                e = t.next(),
                                                o.label = 3;
                                            case 3:
                                                return e.done ? [3, 6] : (c = u(e.value, 2),
                                                s = c[1],
                                                l = (v = r).push,
                                                [4, s.flush(n)]);
                                            case 4:
                                                l.apply(v, [o.sent()]),
                                                o.label = 5;
                                            case 5:
                                                return e = t.next(),
                                                [3, 3];
                                            case 6:
                                                return [3, 9];
                                            case 7:
                                                return y = o.sent(),
                                                d = {
                                                    error: y
                                                },
                                                [3, 9];
                                            case 8:
                                                try {
                                                    e && !e.done && (p = t.return) && p.call(t)
                                                } finally {
                                                    if (d)
                                                        throw d.error
                                                }
                                                return [7];
                                            case 9:
                                                return [2, r.every((function(n) {
                                                    return n
                                                }
                                                ))]
                                            }
                                        }
                                        ))
                                    }
                                    ))
                                }
                            }
                        }
                    }
                    ,
                    n.Sentry = n.Sentry || {},
                    n.Sentry.Integrations = n.Sentry.Integrations || {},
                    r)
                        Object.prototype.hasOwnProperty.call(r, d) && (n.Sentry.Integrations[d] = r[d],
                        n.Sentry[d] = r[d])
                }(window);
            </script>
            <!-- Sentry's moduleMetadataIntegration -->
            <script src="https://browser.sentry-cdn.com/7.120.3/modulemetadata.es5.min.js" crossorigin="anonymous"></script>
            <script>
                window.resolveExternalsRegistryPromise = null
                const externalRegistryPromise = new Promise( (r) => window.resolveExternalsRegistryPromise = r)
                window.resolveExternalsRegistryModule = (name) => externalRegistryPromise.then( () => window.externalsRegistry[name].onload())
            </script>
            <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/externals-registry.inline.a7ae621e.bundle.min.js">
                "use strict";
                (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[9420], {
                    42243: () => {
                        window.__imageClientApi__ = window.__imageClientApi__ || {
                            sdk: {}
                        };
                        const {lodash: e, react: o, reactDOM: a, imageClientApi: n, clientSdk: d} = window.externalsRegistry = {
                            lodash: {},
                            react: {},
                            reactDOM: {},
                            imageClientApi: {},
                            clientSdk: {}
                        };
                        n.loaded = new Promise((e => {
                            n.onload = e
                        }
                        )),
                        e.loaded = new Promise((o => {
                            e.onload = o
                        }
                        )),
                        d.loaded = new Promise((e => {
                            d.onload = e
                        }
                        )),
                        window.ReactDOM || (window.reactDOMReference = window.ReactDOM = {
                            loading: !0
                        }),
                        a.loaded = new Promise((e => {
                            a.onload = () => {
                                Object.assign(window.reactDOMReference || {}, window.ReactDOM, {
                                    loading: !1
                                }),
                                e()
                            }
                        }
                        )),
                        window.React || (window.reactReference = window.React = {
                            loading: !0
                        }),
                        o.loaded = new Promise((e => {
                            o.onload = () => {
                                Object.assign(window.reactReference || {}, window.React, {
                                    loading: !1
                                }),
                                e()
                            }
                        }
                        )),
                        window.reactAndReactDOMLoaded = Promise.all([o.loaded, a.loaded]),
                        window.resolveExternalsRegistryPromise()
                    }
                }, e => {
                    var o;
                    o = 42243,
                    e(e.s = o)
                }
                ]);
                //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/externals-registry.inline.a7ae621e.bundle.min.js.map
            </script>
            <!-- Add the rest of the ViewerModel -->
            <script type="application/json" id="wix-viewer-model">
                {
                    "siteAssetsTestModuleVersion": "1.334.0",
                    "requestUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                    "siteFeatures": [
                        "appMonitoring",
                        "assetsLoader",
                        "businessLogger",
                        "captcha",
                        "clickHandlerRegistrar",
                        "commonConfig",
                        "componentsLoader",
                        "componentsRegistry",
                        "consentPolicy",
                        "cyclicTabbing",
                        "environmentWixCodeSdk",
                        "environment",
                        "locationWixCodeSdk",
                        "mpaNavigation",
                        "navigationManager",
                        "navigationPhases",
                        "ooi",
                        "pages",
                        "panorama",
                        "renderer",
                        "reporter",
                        "router",
                        "scrollRestoration",
                        "seoWixCodeSdk",
                        "seo",
                        "sessionManager",
                        "siteMembersWixCodeSdk",
                        "siteMembers",
                        "siteScrollBlocker",
                        "siteWixCodeSdk",
                        "stores",
                        "structureApi",
                        "thunderboltInitializer",
                        "tpaCommons",
                        "translations",
                        "usedPlatformApis",
                        "warmupData",
                        "windowMessageRegistrar",
                        "windowWixCodeSdk",
                        "wixEmbedsApi",
                        "componentsReact",
                        "platform"
                    ],
                    "site": {
                        "metaSiteId": "736c7394-4e87-4a3c-9265-7dad8dc29df5",
                        "userId": "927f0172-f6f8-4f97-9d48-2e8dbcef319a",
                        "siteId": "2538b395-fb67-480b-aef2-fd071e6b62dd",
                        "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                        "siteRevision": 28,
                        "siteType": "UGC",
                        "dc": "84",
                        "isResponsive": false,
                        "editorName": "Unknown",
                        "sessionId": "ffa2785f-d71b-404e-a70a-fc343b1b3785",
                        "isSEO": false,
                        "appNameForBiEvents": "thunderbolt"
                    },
                    "isMobileDevice": false,
                    "viewMode": "desktop",
                    "formFactor": "desktop",
                    "deviceInfo": {
                        "deviceClass": "Desktop"
                    },
                    "media": {
                        "staticMediaUrl": "https:\/\/static.wixstatic.com\/media",
                        "mediaRootUrl": "https:\/\/static.wixstatic.com\/",
                        "staticVideoUrl": "https:\/\/video.wixstatic.com\/"
                    },
                    "language": {
                        "userLanguage": "en",
                        "userLanguageResolutionMethod": "QueryParam",
                        "siteLanguage": "en",
                        "isMultilingualEnabled": false,
                        "directionByLanguage": "ltr"
                    },
                    "mode": {
                        "qa": false,
                        "enableTestApi": false,
                        "debug": false,
                        "ssrIndicator": false,
                        "ssrOnly": false,
                        "siteAssetsFallback": "enable",
                        "versionIndicator": false
                    },
                    "siteFeaturesConfigs": {
                        "appMonitoring": {
                            "appsWithMonitoring": [
                            ]
                        },
                        "assetsLoader": {
                            "isStylableComponentInStructure": false
                        },
                        "componentsRegistry": {
                            "librariesTopology": [
                                {
                                    "artifactId": "editor-elements",
                                    "namespace": "wixui",
                                    "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                                },
                                {
                                    "artifactId": "editor-elements",
                                    "namespace": "dsgnsys",
                                    "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                                }
                            ]
                        },
                        "consentPolicy": {
                            "isWixSite": false
                        },
                        "dataWixCodeSdk": {
                            "gridAppId": "e597d3b3-fe3f-4a82-901e-03cc5bfb37f9",
                            "environment": "LIVE",
                            "cloudDataUrlWithExternalBase": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/cloud-data"
                        },
                        "elementorySupportWixCodeSdk": {
                            "baseUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/wix-code-public-dispatcher-ng\/siteview",
                            "relativePath": "\/author\/_api\/wix-code-public-dispatcher-ng\/siteview",
                            "gridAppId": "e597d3b3-fe3f-4a82-901e-03cc5bfb37f9",
                            "viewMode": "site",
                            "siteRevision": 28
                        },
                        "environmentWixCodeSdk": {
                        },
                        "environment": {
                            "editorType": "",
                            "domain": "wixsite.com",
                            "previewMode": false
                        },
                        "fedopsWixCodeSdk": {
                            "isWixSite": false,
                            "shouldReportFedops": false
                        },
                        "locationWixCodeSdk": {
                            "routersConfigMap": {
                            },
                            "urlMappings": null
                        },
                        "mpaNavigation": {
                            "forceMpaNavigation": false
                        },
                        "ooiTpaSharedConfig": {
                            "imageSpriteUrl": "https:\/\/static.parastorage.com\/services\/santa-resources\/resources\/viewer\/editorUI\/fonts.v19.png",
                            "wixStaticFontsLinks": [
                                "https:\/\/static.parastorage.com\/services\/fonts-data\/dist\/fonts.mjtd3c8n2u3hi9zejjn2.css",
                                "https:\/\/static.parastorage.com\/services\/fonts-data\/dist\/wixMadefor.lhwa62d5phtg3i69bmvs.css",
                                ""
                            ]
                        },
                        "ooi": {
                            "ooiComponentsData": {
                                "371ee199-389c-4a93-849e-e35b8a15b7ca": {
                                    "sentryDsn": "https:\/\/18d2f96d279149989b95faf0a4b41882@sentry-next.wixpress.com\/1784",
                                    "componentUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/FormViewerWidget.bundle.min.js",
                                    "widgetId": "371ee199-389c-4a93-849e-e35b8a15b7ca",
                                    "noCssComponentUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/FormViewerWidgetNoCss.bundle.min.js",
                                    "staticBaseUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0",
                                    "isLoadable": true,
                                    "isServerBundled": false,
                                    "loadStaticCssWithLink": true,
                                    "isModuleFederated": false
                                }
                            },
                            "viewMode": "Site",
                            "formFactor": "Desktop",
                            "blogMobileComponentUrl": "undefinedfeed-page-mobile-viewer.bundle.min.js"
                        },
                        "renderer": {
                            "disabledComponents": {
                            }
                        },
                        "reporter": {
                            "userId": "927f0172-f6f8-4f97-9d48-2e8dbcef319a",
                            "metaSiteId": "736c7394-4e87-4a3c-9265-7dad8dc29df5",
                            "isPremium": false,
                            "isFBServerEventsAppProvisioned": false,
                            "dynamicPagesIds": [
                            ]
                        },
                        "router": {
                            "baseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                            "mainPageId": "c1dmp",
                            "pagesMap": {
                                "xj8t2": {
                                    "pageId": "xj8t2",
                                    "title": "Bio",
                                    "pageUriSEO": "bio",
                                    "pageJsonFileName": "927f01_4b5e6d26efa85619aaa66cf425c60e93_26"
                                },
                                "nb2bz": {
                                    "pageId": "nb2bz",
                                    "title": "Contact",
                                    "pageUriSEO": "contact",
                                    "pageJsonFileName": "927f01_da194d9ff6be702f29792698eb4b1f12_26"
                                },
                                "azbrr": {
                                    "pageId": "azbrr",
                                    "title": "Projects",
                                    "pageUriSEO": "projects",
                                    "pageJsonFileName": "927f01_5b24ce26706a4d3498ba1a75dc537cc3_25"
                                },
                                "c1dmp": {
                                    "pageId": "c1dmp",
                                    "title": "Home",
                                    "pageUriSEO": "home",
                                    "pageJsonFileName": "927f01_79b9b617722cbbb20fd8bc2410d724f3_28"
                                }
                            },
                            "disableStaticPagesUrlHierarchy": false,
                            "routes": {
                                ".\/bio": {
                                    "type": "Static",
                                    "pageId": "xj8t2"
                                },
                                ".\/contact": {
                                    "type": "Static",
                                    "pageId": "nb2bz"
                                },
                                ".\/projects": {
                                    "type": "Static",
                                    "pageId": "azbrr"
                                },
                                ".\/home": {
                                    "type": "Static",
                                    "pageId": "c1dmp"
                                },
                                ".\/": {
                                    "type": "Static",
                                    "pageId": "c1dmp"
                                }
                            },
                            "pageIdToPrefix": {
                            },
                            "isWixSite": false,
                            "partialRouteMatchingAllowed": false
                        },
                        "searchWixCodeSdk": {
                            "language": "en"
                        },
                        "seo": {
                            "context": {
                                "siteName": "Author",
                                "siteUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                "domain": "wixsite.com",
                                "indexSite": true,
                                "defaultUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                "currLangIsOriginal": true,
                                "homePageTitle": "Home",
                                "businessName": "Amüre W. Anat",
                                "businesLocale": "es-es",
                                "businessLocationCountry": "ES",
                                "businessLocationFormatted": "Alicante, Spain",
                                "businesLocationsState": "VC",
                                "businessLocationCity": "Alicante",
                                "businessLocationCoordinates": {
                                    "latitude": 38.3457685,
                                    "longitude": -0.4909444
                                },
                                "businessSchedule": {
                                },
                                "currency": "EUR",
                                "experiments": {
                                    "specs.seo.EnableFaqSD": "false",
                                    "specs.seo.EnableOnlineProgramsVideoSD": "true"
                                },
                                "platformAppsExperiments": {
                                    "14ce1214-b278-a7e4-1373-00cebd1bef7c": {
                                        "specs.forms.EnableFormsInBlog": "true"
                                    },
                                    "225dd912-7dea-4738-8688-4b8c6955ffc2": {
                                        "specs.forms.LocalPhoneNumbers": "false",
                                        "specs.form-app.AiFormAssistantTypingEffect": "false",
                                        "specs.forms.MultilineAddressInTemplates": "true",
                                        "specs.forms.UseCSSVarsOnly": "true",
                                        "specs.forms.SettingsButtonTextFormatting": "true",
                                        "specs.forms.ComposerSoftDefaultStyleFormApp": "false",
                                        "spec.forms.ClearFieldsWhenHiddenByRule": "true",
                                        "specs.forms.SubmitStatusMessageViewer": "true",
                                        "specs.forms.UseFieldsV2": "false",
                                        "specs.form-app.AiFormAssistantV2": "false",
                                        "specs.forms.FileUploadLimitExceeded": "true",
                                        "specs.forms.ImportFilesToMediaManagerExperiment": "true",
                                        "specs.form-app.AiFormAssistantOptionsButtons": "true",
                                        "specs.forms.UseCustomErrorMessages": "true",
                                        "specs.forms.EnableNewPhoneFieldValidation": "true",
                                        "specs.forms.EnablePhoneField": "true",
                                        "specs.forms.EnablePresetTab": "false",
                                        "specs.forms.EnableDextPhoneField": "true"
                                    },
                                    "675bbcef-18d8-41f5-800e-131ec9e08762": {
                                        "specs.wixCode.LoadWithImportAMDModule": "true",
                                        "specs.wixCode.LoadNamespacesPerPage": "false",
                                        "specs.wixcode.ViewerExperimentOwnerScopeTest": "true",
                                        "specs.wixCode.resolveMissingPlatformNamespaces": "false",
                                        "specs.wixcode.ViewerExperimentTest": "false"
                                    }
                                }
                            },
                            "userPatterns": [
                            ],
                            "metaTags": [
                                {
                                    "name": "fb_admins_meta_tag",
                                    "value": "",
                                    "property": false
                                }
                            ],
                            "customHeadTags": "",
                            "isInSEO": false,
                            "hasBlogAmp": false,
                            "mainPageId": "c1dmp"
                        },
                        "sessionManager": {
                            "sessionModel": {
                            },
                            "appsInstances": {
                            },
                            "dynamicModelApiUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/v2\/dynamicmodel",
                            "accessTokensApiUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/v1\/access-tokens",
                            "expiryTimeoutOverride": 0,
                            "isRunningInDifferentSiteContext": false
                        },
                        "siteMembersWixCodeSdk": {
                            "isPreviewMode": false,
                            "isEditMode": false,
                            "smToken": "",
                            "smcollectionId": "cd38a483-45b9-4a27-b4fd-0ea378417f13"
                        },
                        "siteMembers": {
                            "collectionExposure": "Public",
                            "smcollectionId": "cd38a483-45b9-4a27-b4fd-0ea378417f13",
                            "smToken": "",
                            "protectedHomepage": false,
                            "isTemplate": false,
                            "loginSocialBarOnSite": false,
                            "isCommunityInstalled": false
                        },
                        "siteWixCodeSdk": {
                            "fontFaceServerUrl": "https:\/\/serverless.parastorage.com\/_serverless\/site-sdk-server\/v1\/style",
                            "siteDisplayName": "Author",
                            "siteRevision": 28,
                            "regionalSettings": "es-es",
                            "language": "en",
                            "prefetchPageResourcesEnabled": true,
                            "currency": "EUR",
                            "mainPageId": "c1dmp",
                            "pageIdToPrefix": {
                            },
                            "routerPrefixes": {
                            },
                            "timezone": "Europe\/Madrid",
                            "pageIdToTitle": {
                                "xj8t2": "Bio",
                                "nb2bz": "Contact",
                                "azbrr": "Projects",
                                "c1dmp": "Home"
                            },
                            "urlMappings": null,
                            "viewMode": "Site"
                        },
                        "tpaCommons": {
                            "widgetsClientSpecMapData": {
                                "141995eb-c700-8487-6366-a482f7432e2b": {
                                    "widgetUrl": "https:\/\/so-feed.codev.wixapps.net\/widget",
                                    "mobileUrl": "https:\/\/so-feed.codev.wixapps.net\/widget",
                                    "tpaWidgetId": "shoutout_feed",
                                    "appPage": {
                                    },
                                    "applicationId": 23,
                                    "appDefinitionName": "ShoutOut (Legacy)",
                                    "appDefinitionId": "135c3d92-0fea-1f9d-2ba5-2a1dfb04297e",
                                    "isWixTPA": true,
                                    "allowScrolling": false
                                },
                                "371ee199-389c-4a93-849e-e35b8a15b7ca": {
                                    "widgetUrl": "https:\/\/editor.wixapps.net\/render\/prod\/editor\/form-app\/1.1636.0\/Form",
                                    "mobileUrl": "https:\/\/editor.wixapps.net\/render\/prod\/editor\/form-app\/1.1636.0\/Form",
                                    "tpaWidgetId": "371ee199-389c-4a93-849e-e35b8a15b7ca",
                                    "appPage": {
                                    },
                                    "applicationId": 4274,
                                    "appDefinitionName": "Wix Forms",
                                    "appDefinitionId": "225dd912-7dea-4738-8688-4b8c6955ffc2",
                                    "isWixTPA": true,
                                    "allowScrolling": false
                                }
                            },
                            "appsClientSpecMapData": {
                                "135c3d92-0fea-1f9d-2ba5-2a1dfb04297e": {
                                    "applicationId": 23,
                                    "widgets": {
                                        "141995eb-c700-8487-6366-a482f7432e2b": {
                                            "widgetUrl": "https:\/\/so-feed.codev.wixapps.net\/widget",
                                            "widgetId": "141995eb-c700-8487-6366-a482f7432e2b",
                                            "refreshOnWidthChange": true,
                                            "mobileUrl": "https:\/\/so-feed.codev.wixapps.net\/widget",
                                            "published": true,
                                            "mobilePublished": true,
                                            "seoEnabled": true,
                                            "preFetch": false,
                                            "shouldBeStretchedByDefault": false,
                                            "shouldBeStretchedByDefaultMobile": false,
                                            "componentFields": {
                                            },
                                            "tpaWidgetId": "shoutout_feed",
                                            "default": true
                                        }
                                    },
                                    "appDefinitionName": "ShoutOut (Legacy)",
                                    "appFields": {
                                        "premiumBundle": {
                                            "parentAppSlug": "ee21fe60-48c5-45e9-95f4-6ca8f9b1c9d9",
                                            "parentAppId": "ee21fe60-48c5-45e9-95f4-6ca8f9b1c9d9"},
                                            "permissionsEnforced": false,
                                            "blocksPermissionsEnforced": false,
                                            "isStandalone": true,
                                            "semanticVersion": "^0.1802.0"
                                        },
                                        "isWixTPA": true
                                    },
                                    "225dd912-7dea-4738-8688-4b8c6955ffc2": {
                                        "applicationId": 4274,
                                        "widgets": {
                                            "371ee199-389c-4a93-849e-e35b8a15b7ca": {
                                                "widgetUrl": "https:\/\/editor.wixapps.net\/render\/prod\/editor\/form-app\/1.1636.0\/Form",
                                                "widgetId": "371ee199-389c-4a93-849e-e35b8a15b7ca",
                                                "refreshOnWidthChange": true,
                                                "mobileUrl": "https:\/\/editor.wixapps.net\/render\/prod\/editor\/form-app\/1.1636.0\/Form",
                                                "published": true,
                                                "mobilePublished": true,
                                                "seoEnabled": false,
                                                "shouldBeStretchedByDefault": false,
                                                "shouldBeStretchedByDefaultMobile": false,
                                                "componentFields": {
                                                    "mobileSettingsEnabled": true,
                                                    "viewer": {
                                                        "errorReporting": {
                                                            "url": "https:\/\/18d2f96d279149989b95faf0a4b41882@sentry-next.wixpress.com\/1784"
                                                        }
                                                    },
                                                    "noCssComponentUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/FormViewerWidgetNoCss.bundle.min.js",
                                                    "componentUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/FormViewerWidget.bundle.min.js",
                                                    "cssPerBreakpoint": true,
                                                    "ssrCacheExcluded": "false",
                                                    "isLoadable": true,
                                                    "ooiInEditor": true
                                                },
                                                "tpaWidgetId": "371ee199-389c-4a93-849e-e35b8a15b7ca",
                                                "default": true
                                            }
                                        },
                                        "appDefinitionName": "Wix Forms",
                                        "appFields": {
                                            "platform": {
                                                "baseUrls": {
                                                    "staticsBaseUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0",
                                                    "staticsEditorBaseUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0"
                                                },
                                                "baseUrlsTemplate": {
                                                    "staticsBaseUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0"
                                                },
                                                "editorScriptUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/editorScript.bundle.min.js",
                                                "viewerScriptUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/viewerScript.bundle.min.js",
                                                "errorReporting": {
                                                    "url": "https:\/\/5d1795a2db124a268f1e1bd88f503500@sentry.wixpress.com\/4615"
                                                },
                                                "viewer": {
                                                    "errorReporting": {
                                                        "url": "https:\/\/5d1795a2db124a268f1e1bd88f503500@sentry.wixpress.com\/4615"
                                                    }
                                                },
                                                "ooiInEditor": true
                                            },
                                            "permissionsEnforced": false,
                                            "blocksPermissionsEnforced": false,
                                            "isStandalone": true,
                                            "semanticVersion": "^0.611.0"
                                        },
                                        "isWixTPA": true
                                    }
                                },
                                "previewMode": false,
                                "siteRevision": 28,
                                "userFileDomainUrl": "filesusr.com",
                                "metaSiteId": "736c7394-4e87-4a3c-9265-7dad8dc29df5",
                                "isPremiumDomain": false,
                                "routersConfig": {
                                },
                                "routerByPrefix": {
                                },
                                "pageIdToPrefix": {
                                },
                                "viewMode": "site",
                                "editorOrSite": "site",
                                "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                "tpaModalConfig": {
                                    "wixTPAs": {
                                        "139ef4fa-c108-8f9a-c7be-d5f492a2c939": true,
                                        "4b10fcce-732d-4be3-9d46-801d271acda9": true,
                                        "13ee94c1-b635-8505-3391-97919052c16f": true,
                                        "55cd9036-36bb-480b-8ddc-afda3cb2eb8d": true,
                                        "35aec784-bbec-4e6e-abcb-d3d724af52cf": true,
                                        "8ea9df15-9ff6-4acf-bbb8-8d3a69ae5841": true,
                                        "141fbfae-511e-6817-c9f0-48993a7547d1": true,
                                        "135c3d92-0fea-1f9d-2ba5-2a1dfb04297e": true,
                                        "7efa9936-86f7-44c6-880b-7bae4e044a3d": true,
                                        "14ce1214-b278-a7e4-1373-00cebd1bef7c": true,
                                        "d70b68e2-8d77-4e0c-9c00-c292d6e0025e": true,
                                        "146c0d71-352e-4464-9a03-2e868aabe7b9": true,
                                        "307ba931-689c-4b55-bb1d-6a382bad9222": true,
                                        "14b89688-9b25-5214-d1cb-a3fb9683618b": true,
                                        "ea2821fc-7d97-40a9-9f75-772f29178430": true,
                                        "9bead16f-1c73-4cda-b6c4-28cff46988db": true,
                                        "1480c568-5cbd-9392-5604-1148f5faffa0": true,
                                        "94bc563b-675f-41ad-a2a6-5494f211c47b": true,
                                        "14e12b04-943e-fd32-456d-70b1820a2ff2": true,
                                        "14bca956-e09f-f4d6-14d7-466cb3f09103": true,
                                        "150ae7ee-c74a-eecd-d3d7-2112895b988a": true,
                                        "f123e8f1-4350-4c9b-b269-04adfadda977": true,
                                        "225dd912-7dea-4738-8688-4b8c6955ffc2": true
                                    }
                                },
                                "appSectionParams": {
                                },
                                "requestUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                "isMobileView": false,
                                "deviceType": "desktop",
                                "isMobileDevice": false,
                                "extras": {
                                    "currency": "EUR"
                                },
                                "tpaDebugParams": {
                                    "debugApp": null,
                                    "petri_ovr": null
                                },
                                "locale": "en",
                                "timeZone": "Europe\/Madrid",
                                "shouldRenderTPAsIframe": true,
                                "debug": false,
                                "regionalLanguage": "en"
                            },
                            "windowWixCodeSdk": {
                                "locale": "es-es",
                                "isMobileFriendly": true,
                                "formFactor": "Desktop",
                                "pageIdToRouterAppDefinitionId": {
                                }
                            },
                            "wixEmbedsApi": {
                                "isAdminPage": false
                            },
                            "platform": {
                                "sdksStaticPaths": {
                                    "mainSdks": "https:\/\/static.parastorage.com\/services\/wix-thunderbolt\/dist\/mainSdks.25e19034.chunk.min.js",
                                    "nonMainSdks": "https:\/\/static.parastorage.com\/services\/wix-thunderbolt\/dist\/nonMainSdks.f808eefb.chunk.min.js"
                                },
                                "landingPageId": "c1dmp",
                                "isChancePlatformOnLandingPage": false,
                                "clientWorkerUrl": "https:\/\/static.parastorage.com\/services\/wix-thunderbolt\/dist\/clientWorker.4ed670d6.bundle.min.js",
                                "bootstrapData": {
                                    "isMobileView": false,
                                    "isMobileAppBuilder": false,
                                    "appsSpecData": {
                                        "14ce1214-b278-a7e4-1373-00cebd1bef7c": {
                                            "appDefinitionId": "14ce1214-b278-a7e4-1373-00cebd1bef7c",
                                            "type": "public",
                                            "instanceId": "7278edad-ca65-4dc9-a24b-810b3541acc4",
                                            "appDefinitionName": "Old Wix Forms and Payments",
                                            "isWixTPA": true,
                                            "isModuleFederated": false
                                        },
                                        "675bbcef-18d8-41f5-800e-131ec9e08762": {
                                            "appDefinitionId": "675bbcef-18d8-41f5-800e-131ec9e08762",
                                            "type": "siteextension",
                                            "instanceId": "b5ea632b-cc6c-4268-9a6f-cdfb54b067c4",
                                            "isModuleFederated": false
                                        },
                                        "225dd912-7dea-4738-8688-4b8c6955ffc2": {
                                            "appDefinitionId": "225dd912-7dea-4738-8688-4b8c6955ffc2",
                                            "type": "public",
                                            "instanceId": "4177b686-841a-4513-b63e-0f3726746b03",
                                            "appDefinitionName": "Wix Forms",
                                            "isWixTPA": true,
                                            "isModuleFederated": false
                                        },
                                        "dataBinding": {
                                            "appDefinitionId": "dataBinding",
                                            "type": "application",
                                            "instanceId": "b5ea632b-cc6c-4268-9a6f-cdfb54b067c4",
                                            "appDefinitionName": "Data Binding",
                                            "isWixTPA": true,
                                            "isModuleFederated": false
                                        }
                                    },
                                    "appsUrlData": {
                                        "14ce1214-b278-a7e4-1373-00cebd1bef7c": {
                                            "appDefId": "14ce1214-b278-a7e4-1373-00cebd1bef7c",
                                            "appDefName": "Old Wix Forms and Payments",
                                            "viewerScriptUrl": "https:\/\/static.parastorage.com\/services\/forms-viewer\/1.883.0\/viewerScript.bundle.min.js",
                                            "baseUrls": {
                                            },
                                            "widgets": {
                                            }
                                        },
                                        "225dd912-7dea-4738-8688-4b8c6955ffc2": {
                                            "appDefId": "225dd912-7dea-4738-8688-4b8c6955ffc2",
                                            "appDefName": "Wix Forms",
                                            "viewerScriptUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/viewerScript.bundle.min.js",
                                            "baseUrls": {
                                                "staticsBaseUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0",
                                                "staticsEditorBaseUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0"
                                            },
                                            "errorReportingUrl": "https:\/\/5d1795a2db124a268f1e1bd88f503500@sentry.wixpress.com\/4615",
                                            "widgets": {
                                                "371ee199-389c-4a93-849e-e35b8a15b7ca": {
                                                    "controllerUrl": "",
                                                    "componentUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/FormViewerWidget.bundle.min.js",
                                                    "noCssComponentUrl": "https:\/\/static.parastorage.com\/services\/form-app\/1.1636.0\/FormViewerWidgetNoCss.bundle.min.js",
                                                    "errorReportingUrl": "https:\/\/18d2f96d279149989b95faf0a4b41882@sentry-next.wixpress.com\/1784",
                                                    "widgetId": "371ee199-389c-4a93-849e-e35b8a15b7ca",
                                                    "cssPerBreakpoint": true
                                                }
                                            }
                                        },
                                        "dataBinding": {
                                            "appDefId": "dataBinding",
                                            "appDefName": "Data Binding",
                                            "viewerScriptUrl": "https:\/\/static.parastorage.com\/services\/dbsm-viewer-app\/1.8623.0\/app.js",
                                            "baseUrls": {
                                        },
                                        "widgets": {
                                        }
                                    },
                                    "675bbcef-18d8-41f5-800e-131ec9e08762": {
                                        "appDefId": "675bbcef-18d8-41f5-800e-131ec9e08762",
                                        "viewerScriptUrl": "https:\/\/static.parastorage.com\/services\/wix-code-viewer-app\/1.1479.731\/app.js",
                                        "baseUrls": {
                                        },
                                        "widgets": {
                                        }
                                    }
                                },
                                "blocksBootstrapData": {
                                    "blocksAppsData": {
                                    },
                                    "experiments": {
                                    },
                                    "experimentsQueryParams": "analyze-imported-namespaces=true&init-platform-api-provider=true&get-app-def-id-from-package-name=false&disable-yarn-pnp-mode=undefined&bundler-traffic-to-aws=true&bundler-typescript-analysis=true",
                                    "widgetBundleUrls": {
                                    }
                                },
                                "window": {
                                    "csrfToken": "1741278169|LTk0Nwppodp9"
                                },
                                "location": {
                                    "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                    "isPremiumDomain": false,
                                    "metaSiteId": "736c7394-4e87-4a3c-9265-7dad8dc29df5",
                                    "userFileDomainUrl": "filesusr.com"
                                },
                                "bi": {
                                    "ownerId": "927f0172-f6f8-4f97-9d48-2e8dbcef319a",
                                    "isMobileFriendly": true,
                                    "isPreview": false,
                                    "requestId": "1741596377.452168069200534131044"
                                },
                                "platformAPIData": {
                                    "routersConfigMap": {
                                    }
                                },
                                "wixCodeBootstrapData": {
                                    "wixCodeAppDefinitionId": "675bbcef-18d8-41f5-800e-131ec9e08762",
                                    "wixCodeInstanceId": "b5ea632b-cc6c-4268-9a6f-cdfb54b067c4",
                                    "wixCloudBaseDomain": "wix-code.com",
                                    "dbsmViewerApp": "https:\/\/static.parastorage.com\/services\/dbsm-viewer-app\/1.8623.0",
                                    "wixCodePlatformBaseUrl": "https:\/\/static.parastorage.com\/services\/wix-code-platform\/1.1097.93",
                                    "wixCodeModel": {
                                        "appData": {
                                            "codeAppId": "e597d3b3-fe3f-4a82-901e-03cc5bfb37f9"
                                        },
                                        "signedAppRenderInfo": "34b78e938e2832531aa1bdf8ecd2cd0d89e6af9f.eyJncmlkQXBwSWQiOiJlNTk3ZDNiMy1mZTNmLTRhODItOTAxZS0wM2NjNWJmYjM3ZjkiLCJodG1sU2l0ZUlkIjoiMjUzOGIzOTUtZmI2Ny00ODBiLWFlZjItZmQwNzFlNmI2MmRkIiwiZGVtb0lkIjpudWxsLCJzaWduRGF0ZSI6MTc0MTU5NjM3NzUwN30="
                                    },
                                    "wixCodePageIds": {
                                    },
                                    "elementorySupport": {
                                        "baseUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/wix-code-public-dispatcher-ng\/siteview"
                                    },
                                    "codePackagesData": [
                                    ]
                                },
                                "autoFrontendModulesBaseUrl": "https:\/\/static.parastorage.com\/services\/auto-frontend-modules\/1.6238.0",
                                "disabledPlatformApps": {
                                },
                                "widgetsClientSpecMapData": {
                                    "14ce1214-b278-a7e4-1373-00cebd1bef7c": {
                                    },
                                    "675bbcef-18d8-41f5-800e-131ec9e08762": {
                                    },
                                    "225dd912-7dea-4738-8688-4b8c6955ffc2": {
                                        "371ee199-389c-4a93-849e-e35b8a15b7ca": {
                                            "widgetName": "371ee199-389c-4a93-849e-e35b8a15b7ca",
                                            "componentFields": {
                                            }
                                        }
                                    },
                                    "dataBinding": {
                                    }
                                },
                                "essentials": {
                                    "appsConductedExperiments": {
                                        "14ce1214-b278-a7e4-1373-00cebd1bef7c": {
                                            "specs.forms.EnableFormsInBlog": "true"
                                        },
                                        "225dd912-7dea-4738-8688-4b8c6955ffc2": {
                                            "specs.forms.LocalPhoneNumbers": "false",
                                            "specs.form-app.AiFormAssistantTypingEffect": "false",
                                            "specs.forms.MultilineAddressInTemplates": "true",
                                            "specs.forms.UseCSSVarsOnly": "true",
                                            "specs.forms.SettingsButtonTextFormatting": "true",
                                            "specs.forms.ComposerSoftDefaultStyleFormApp": "false",
                                            "spec.forms.ClearFieldsWhenHiddenByRule": "true",
                                            "specs.forms.SubmitStatusMessageViewer": "true",
                                            "specs.forms.UseFieldsV2": "false",
                                            "specs.form-app.AiFormAssistantV2": "false",
                                            "specs.forms.FileUploadLimitExceeded": "true",
                                            "specs.forms.ImportFilesToMediaManagerExperiment": "true",
                                            "specs.form-app.AiFormAssistantOptionsButtons": "true",
                                            "specs.forms.UseCustomErrorMessages": "true",
                                            "specs.forms.EnableNewPhoneFieldValidation": "true",
                                            "specs.forms.EnablePhoneField": "true",
                                            "specs.forms.EnablePresetTab": "false",
                                            "specs.forms.EnableDextPhoneField": "true"},
                                            "675bbcef-18d8-41f5-800e-131ec9e08762": {
                                                "specs.wixCode.LoadWithImportAMDModule": "true",
                                                "specs.wixCode.LoadNamespacesPerPage": "false",
                                                "specs.wixcode.ViewerExperimentOwnerScopeTest": "true",
                                                "specs.wixCode.resolveMissingPlatformNamespaces": "false",
                                                "specs.wixcode.ViewerExperimentTest": "false"
                                            }
                                        }
                                    },
                                    "forceEmptySdks": false,
                                    "appDefIdToIsMigratedToGetPlatformApi": {
                                        "14ce1214-b278-a7e4-1373-00cebd1bef7c": false,
                                        "675bbcef-18d8-41f5-800e-131ec9e08762": false,
                                        "225dd912-7dea-4738-8688-4b8c6955ffc2": false,
                                        "dataBinding": false
                                    }
                                },
                                "appsScripts": {
                                    "urls": {
                                    },
                                    "scope": "page"
                                },
                                "debug": {
                                    "disablePlatform": false,
                                    "disableSnapshots": false,
                                    "enableSnapshots": false
                                }}
                            },
                            "siteAssets": {
                                "dataFixersParams": {
                                    "experiments": {
                                        "specs.thunderbolt.use_data_fixed_pages_upstream": true,
                                        "dm_deleteLayoutOverridesForRefComponents": true,
                                        "dm_migrateOldHoverBoxToNewFixer": true,
                                        "dm_removeTpaChildren": true,
                                        "dm_bgScrubToMotionFixer": true
                                    },
                                    "dfVersion": "1.4468.0",
                                    "isHttps": true,
                                    "isUrlMigrated": true,
                                    "metaSiteId": "736c7394-4e87-4a3c-9265-7dad8dc29df5",
                                    "quickActionsMenuEnabled": false,
                                    "siteId": "2538b395-fb67-480b-aef2-fd071e6b62dd",
                                    "siteRevision": 28,
                                    "v": 3,
                                    "cacheVersions": {
                                        "dataFixer": 6
                                    },
                                    "oneDocEnabled": true
                                },
                                "modulesParams": {
                                    "features": {
                                        "moduleName": "thunderbolt-features",
                                        "contentType": "application\/json",
                                        "resourceType": "features",
                                        "languageResolutionMethod": "QueryParam",
                                        "isMultilingualEnabled": false,
                                        "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                        "useSandboxInHTMLComp": true,
                                        "disableStaticPagesUrlHierarchy": false,
                                        "aboveTheFoldSectionsNum": null,
                                        "isTrackClicksAnalyticsEnabled": false,
                                        "isSocialElementsBlocked": false},
                                        "platform": {
                                            "moduleName": "thunderbolt-platform",
                                            "contentType": "application\/json",
                                            "resourceType": "platform",
                                            "externalBaseUrl": "https:\/\/aishtapamura.wixsite.com\/author",
                                            "staticHTMLComponentUrl": "https:\/\/aishtapamura-wixsite-com.filesusr.com\/"
                                        },
                                        "css": {
                                            "moduleName": "thunderbolt-css",
                                            "contentType": "application\/json",
                                            "resourceType": "css",
                                            "shouldRunVsm": true,
                                            "shouldRunCssInBrowser": false,
                                            "shouldGetCssResultObject": false,
                                            "stylableMetadataURLs": [
                                                "editor-elements-library.thunderbolt.0617c1818099a54bf3950940a60571920a778ce1",
                                                "editor-elements-design-systems.thunderbolt.8487b46c0a33e714158da9c35ab5449672773575"
                                            ],
                                            "ooiVersions": "371ee199-389c-4a93-849e-e35b8a15b7ca%3Dp.form-app%2F1.1636.0%2FFormViewerWidgetNoCss."
                                        },
                                        "cssMappers": {
                                            "moduleName": "thunderbolt-css-mappers",
                                            "contentType": "application\/json",
                                            "resourceType": "cssMappers",
                                            "shouldRunVsm": true,
                                            "shouldRunCssInBrowser": false,
                                            "shouldGetCssResultObject": false,
                                            "stylableMetadataURLs": [
                                                "editor-elements-library.thunderbolt.0617c1818099a54bf3950940a60571920a778ce1",
                                                "editor-elements-design-systems.thunderbolt.8487b46c0a33e714158da9c35ab5449672773575"
                                            ],
                                            "ooiVersions": "371ee199-389c-4a93-849e-e35b8a15b7ca%3Dp.form-app%2F1.1636.0%2FFormViewerWidgetNoCss."
                                        },
                                        "siteMap": {
                                            "moduleName": "thunderbolt-site-map",
                                            "contentType": "application\/json",
                                            "resourceType": "siteMap"
                                        },
                                        "mobileAppBuilder": {
                                            "moduleName": "thunderbolt-mobile-app-builder",
                                            "resourceType": "mobileAppBuilder",
                                            "contentType": "application\/json"
                                        },
                                        "builderComponentFeatures": {
                                            "moduleName": "builder-component-features",
                                            "resourceType": "builderComponentFeatures",
                                            "contentType": "application\/json"
                                        },
                                        "builderComponentCss": {
                                            "moduleName": "builder-component-css",
                                            "resourceType": "builderComponentCss",
                                            "contentType": "application\/json"
                                        },
                                        "builderComponentPlatform": {
                                            "moduleName": "builder-component-platform",
                                            "resourceType": "builderComponentPlatform",
                                            "contentType": "application\/json"
                                        }
                                    },
                                    "clientTopology": {
                                        "mediaRootUrl": "https:\/\/static.wixstatic.com",
                                        "staticMediaUrl": "https:\/\/static.wixstatic.com\/media",
                                        "moduleRepoUrl": "https:\/\/static.parastorage.com\/unpkg",
                                        "fileRepoUrl": "https:\/\/static.parastorage.com\/services",
                                        "siteAssetsUrl": "https:\/\/siteassets.parastorage.com",
                                        "pageJsonServerUrls": [
                                            "https:\/\/pages.parastorage.com",
                                            "https:\/\/staticorigin.wixstatic.com",
                                            "https:\/\/fallback.wix.com\/wix-html-editor-pages-webapp\/page"
                                        ],
                                        "pathOfTBModulesInFileRepoForFallback": "wix-thunderbolt\/dist\/"
                                    },
                                    "siteScopeParams": {
                                        "rendererType": null,
                                        "wixCodePageIds": [
                                        ],
                                        "hasTPAWorkerOnSite": false,
                                        "formFactor": "desktop",
                                        "viewMode": "desktop",
                                        "freemiumBanner": true,
                                        "coBrandingBanner": false,
                                        "dayfulBanner": false,
                                        "mobileActionsMenu": false,
                                        "isWixSite": false,
                                        "editorName": "Unknown",
                                        "urlFormatModel": {
                                            "format": "slash",
                                            "forbiddenPageUriSEOs": [
                                                "app",
                                                "apps",
                                                "_api",
                                                "robots.txt",
                                                "sitemap.xml",
                                                "feed.xml",
                                                "sites"
                                            ],
                                            "pageIdToResolvedUriSEO": {
                                            }
                                        },
                                        "pageJsonFileNames": {
                                            "xj8t2": "927f01_4b5e6d26efa85619aaa66cf425c60e93_26.json",
                                            "nb2bz": "927f01_da194d9ff6be702f29792698eb4b1f12_26.json",
                                            "azbrr": "927f01_5b24ce26706a4d3498ba1a75dc537cc3_25.json",
                                            "c1dmp": "927f01_79b9b617722cbbb20fd8bc2410d724f3_28.json",
                                            "masterPage": "927f01_8304ca32f83b759906075e878bab5230_28.json"
                                        },
                                        "protectedPageIds": [
                                        ],
                                        "routersInfo": {
                                            "configMap": {
                                            }
                                        },
                                        "isPremiumDomain": false,
                                        "disableSiteAssetsCache": false,
                                        "migratingToOoiWidgetIds": "",
                                        "siteRevisionConfig": {
                                        },
                                        "registryLibrariesTopology": [
                                            {
                                                "artifactId": "editor-elements",
                                                "namespace": "wixui",
                                                "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                                            },
                                            {
                                                "artifactId": "editor-elements",
                                                "namespace": "dsgnsys",
                                                "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                                            }
                                        ],
                                        "isInSeo": false,
                                        "language": "en",
                                        "originalLanguage": "en",
                                        "appDefinitionIdToSiteRevision": {
                                        },
                                        "builderWidgetsIds": {
                                        },
                                        "isClientSdkOnSite": false,
                                        "appDefinitionIdsWithCustomCss": [
                                        ]
                                    },
                                    "beckyExperiments": {
                                        "specs.thunderbolt.fetchBlocksDevCenterWidgetIds": true,
                                        "specs.thunderbolt.useInternalBlocksRefType": true,
                                        "specs.thunderbolt.one_cell_grid_display_flex": true,
                                        "specs.thunderbolt.shouldUseResponsiveImages": true,
                                        "specs.thunderbolt.prefetchPageResourcesVeloApi": true,
                                        "specs.thunderbolt.invalidateDocumentData": true,
                                        "specs.thunderbolt.DatePickerPortal": true,
                                        "specs.thunderbolt.updateRichTextSemanticClassNamesOnCorvid": true,
                                        "specs.thunderbolt.DDMenuMigrateCssCarmiMapper": true,
                                        "specs.thunderbolt.buttonUdp": true,
                                        "specs.thunderbolt.useResponsiveImgClassicFixed": true,
                                        "specs.thunderbolt.dataBindingInMasterResponsive": true,
                                        "specs.thunderbolt.removeAllStatesBlocksFix": true,
                                        "specs.thunderbolt.supportStickyToHeaderValueForBlocksPositionDesignVar": true,
                                        "specs.thunderbolt.fiveGridLineStudioSkins": true,
                                        "specs.thunderbolt.useSvgLoaderFeature": true,
                                        "specs.thunderbolt.noHeightOnTextMask": true,
                                        "specs.thunderbolt.LoginBarEnableLoggingInStateInSSR": true,
                                        "specs.thunderbolt.calculateCollapsibleTextLineHeightByFont": true,
                                        "specs.thunderbolt.imageEncodingAVIF": true,
                                        "specs.thunderbolt.dropAppsClientSpecMapByApplicationId": true,
                                        "specs.thunderbolt.changeCssMapperDomApplierSelectorToCss": true,
                                        "specs.thunderbolt.fixHasPinnedChildrenRepeaterCalc": true,
                                        "specs.thunderbolt.TextInputAutoFillFix": true,
                                        "specs.thunderbolt.getSiteOverrideFromAllInflationChain": true,
                                        "specs.thunderbolt.overflowXClipHeaderAndFooter": true,
                                        "specs.thunderbolt.sliderGalleryWAAPI": true,
                                        "specs.thunderbolt.forceNativeAspectRatio": true,
                                        "specs.thunderbolt.supportAutoHeightCompsInLandingPage": true,
                                        "specs.thunderbolt.overflowXClipInMobile": true
                                    },
                                    "manifests": {
                                        "node": {
                                            "modulesToHashes": {
                                                "thunderbolt-features": "16abef83.bundle.min",
                                                "thunderbolt-platform": "a73a5147.bundle.min",
                                                "thunderbolt-css": "92e4587c.bundle.min",
                                                "thunderbolt-site-map": "009d4d80.bundle.min",
                                                "thunderbolt-mobile-app-builder": "bc7ec143.bundle.min",
                                                "thunderbolt-byref": "2cf6a694.bundle.min",
                                                "thunderbolt-remote-structure": "40065a65.bundle.min",
                                                "builder-component-features": "d626b036.bundle.min",
                                                "builder-component-css": "e1c031df.bundle.min",
                                                "builder-component-platform": "60512cb8.bundle.min",
                                                "thunderbolt-css-mappers": "92e4587c.bundle.min"
                                            }
                                        },
                                        "web": {
                                            "modulesToHashes": {
                                                "thunderbolt-features": "fe7de2bc.bundle.min",
                                                "thunderbolt-platform": "21b43c24.bundle.min",
                                                "thunderbolt-css": "4f954dc2.bundle.min",
                                                "thunderbolt-site-map": "7318d8b8.bundle.min",
                                                "thunderbolt-mobile-app-builder": "838b69d8.bundle.min",
                                                "thunderbolt-byref": "b5ef72a6.bundle.min",
                                                "thunderbolt-remote-structure": "9a47ae74.bundle.min",
                                                "builder-component-features": "c52b851b.bundle.min",
                                                "builder-component-css": "054abe31.bundle.min",
                                                "builder-component-platform": "0af09d74.bundle.min",
                                                "thunderbolt-css-mappers": "7a67af69.bundle.min",
                                                "webpack-runtime": "97ae7421.bundle.min"
                                            },
                                            "webpackRuntimeBundle": "97ae7421.bundle.min"
                                        },
                                        "webWorker": {
                                            "modulesToHashes": {
                                                "thunderbolt-features": "369b4dc1.bundle.min",
                                                "thunderbolt-platform": "7b542d6b.bundle.min",
                                                "thunderbolt-css": "9036edea.bundle.min",
                                                "thunderbolt-site-map": "ede44b74.bundle.min",
                                                "thunderbolt-mobile-app-builder": "23e5f1ab.bundle.min",
                                                "thunderbolt-byref": "6a79ddad.bundle.min",
                                                "thunderbolt-remote-structure": "b3bb7b65.bundle.min",
                                                "builder-component-features": "fce1dcdb.bundle.min",
                                                "builder-component-css": "257a6cbc.bundle.min",
                                                "builder-component-platform": "03a7a444.bundle.min",
                                                "thunderbolt-css-mappers": "9036edea.bundle.min"
                                            }
                                        }
                                    },
                                    "staticHTMLComponentUrl": "https:\/\/aishtapamura-wixsite-com.filesusr.com\/",
                                    "remoteWidgetStructureBuilderVersion": "1.251.0",
                                    "blocksBuilderManifestGeneratorVersion": "1.129.0"
                                },
                                "experiments": {
                                    "specs.thunderbolt.hardenCookieStoreAccess": true,
                                    "specs.thunderbolt.fetchBlocksDevCenterWidgetIds": true,
                                    "specs.thunderbolt.videoLazyLoading": true,
                                    "specs.thunderbolt.getSiteOverrideFromAllInflationChain": true,
                                    "specs.thunderbolt.viewport_hydration_extended_react_18": true,
                                    "specs.thunderbolt.inMemoryPaypalAuthToken": true,
                                    "specs.thunderbolt.roundBordersInResponsiveContainer": true,
                                    "specs.thunderbolt.useInternalBlocksRefType": true,
                                    "specs.thunderbolt.PanoramaErrorMonitor": true,
                                    "specs.thunderbolt.userAsFactory": true,
                                    "specs.thunderbolt.getMemberDetailsFromMembersNg": true,
                                    "specs.thunderbolt.UseEEImpress": true,
                                    "specs.thunderbolt.hardenClientGlobals_EventTarget": true,
                                    "specs.thunderbolt.fixDisabledLinkButtonStyles": true,
                                    "specs.thunderbolt.UseEcomFemBi": true,
                                    "specs.thunderbolt.one_cell_grid_display_flex": true,
                                    "specs.thunderbolt.readWidgetPresetsFromMasterPage": true,
                                    "specs.thunderbolt.hardenWindowOpen": true,
                                    "specs.thunderbolt.overflowXClipHeaderAndFooter": true,
                                    "specs.thunderbolt.sliderGalleryWAAPI": true,
                                    "specs.thunderbolt.shouldUseResponsiveImages": true,
                                    "specs.thunderbolt.fedops_enableSampleRateForAppNames": true,
                                    "specs.thunderbolt.prefetchPageResourcesVeloApi": true,
                                    "specs.thunderbolt.excludeInstanceFromQueryParams": true,
                                    "specs.thunderbolt.doNotMarkTemplateCompAsUnmounted": true,
                                    "specs.thunderbolt.removePageClickHandler": true,
                                    "specs.thunderbolt.fixClassNameOverride": true,
                                    "specs.thunderbolt.ComponentsRegistryFixAnonymousDefine": true,
                                    "specs.thunderbolt.invalidateDocumentData": true,
                                    "specs.thunderbolt.newTransitionEndHandlerLogic": true,
                                    "specs.thunderbolt.LoginSocialBarSplitStateProps": true,
                                    "specs.thunderbolt.skipDecodeUri": true,
                                    "specs.thunderbolt.SetNoCacheOnAppError": true,
                                    "specs.thunderbolt.bundlerTrafficToAws": true,
                                    "specs.thunderbolt.reactScriptSyncLoading": true,
                                    "specs.thunderbolt.routeToExternalDispatcher": true,
                                    "specs.thunderbolt.wixRealtimeGetAppTokenFromPlatformUtils": true,
                                    "specs.thunderbolt.newLoginFlowOnProtectedCollection": true,
                                    "specs.thunderbolt.elementorySupportRemoveCommonConfigHeader": true,
                                    "specs.thunderbolt.mergeSkinDefaultsFromRegistry": true,
                                    "specs.thunderbolt.deprecatewixperf": true,
                                    "specs.thunderbolt.useNewRegisterLogin": true,
                                    "specs.thunderbolt.DatePickerPortal": true,
                                    "specs.thunderbolt.removeSendBeat": true,
                                    "specs.thunderbolt.moveLoadableJSBundlesToBody": true,
                                    "specs.os.EnableErrorHandlerInViewer": true,
                                    "specs.thunderbolt.preventApplySessionTokenInSSR": true,
                                    "specs.thunderbolt.ShouldUseNewIAMSocialFlow": true,
                                    "specs.thunderbolt.softFreeze_TextDecoder_TextEncoder": true,
                                    "specs.thunderbolt.useIAMEnabledConnections": true,
                                    "specs.thunderbolt.StoresCartNullOnShippingInfo": true,
                                    "specs.thunderbolt.use_data_fixed_pages_upstream": true,
                                    "specs.thunderbolt.facebookVideoPlayerDimensions": true,
                                    "specs.thunderbolt.useElementoryRelativePath": true,
                                    "specs.thunderbolt.scrollBlockerPackage": true,
                                    "specs.thunderbolt.preventGetMemberDetailsWaterfall": true,
                                    "specs.thunderbolt.harden_URL_JSON": true,
                                    "specs.thunderbolt.wrichtextListInRtl": true,
                                    "specs.thunderbolt.updateRichTextSemanticClassNamesOnCorvid": true,
                                    "specs.thunderbolt.scrollToTopOnNavigation": true,
                                    "specs.thunderbolt.hardenReflect": true,
                                    "specs.thunderbolt.shouldFetchLoginUrlByClientId": true,
                                    "specs.thunderbolt.shouldLoadGoogleSdkEarly": true,
                                    "specs.thunderbolt.loadNewerSentrySdk": true,
                                    "specs.thunderbolt.forceNativeAspectRatio": true,
                                    "specs.thunderbolt.removeServiceWorker": true,
                                    "specs.thunderbolt.siteScrollBlockerWithoutVar": true,
                                    "specs.thunderbolt.shouldUseMemberPrivacySettingsService": true,
                                    "specs.thunderbolt.DDMenuMigrateCssCarmiMapper": true,
                                    "specs.membersArea.LoginBarRemake": true,
                                    "specs.thunderbolt.buttonUdp": true,
                                    "specs.thunderbolt.alwaysApplySessionTokenOnIAM": true,
                                    "specs.thunderbolt.UseBlocksSignedInstance": true,
                                    "specs.thunderbolt.hardenFetchAndXHR": true,
                                    "specs.thunderbolt.useResponsiveImgClassicFixed": true,
                                    "specs.thunderbolt.dataBindingInMasterResponsive": true,
                                    "specs.thunderbolt.removeAllStatesBlocksFix": true,
                                    "specs.thunderbolt.hardenEncodingDecoding": true,
                                    "specs.thunderbolt.StoresCartZeroOnShippingAndTax": true,
                                    "specs.thunderbolt.enableSignUpPrivacyNoteType": true,
                                    "specs.thunderbolt.cssInBlocksNewApi": true,
                                    "specs.thunderbolt.veloWixMembersAmbassadorV2": true,
                                    "specs.thunderbolt.customElemCollapsedheight": true,
                                    "specs.thunderbolt.supportStickyToHeaderValueForBlocksPositionDesignVar": true,
                                    "specs.thunderbolt.megaMenuMouseLeave": true,
                                    "specs.thunderbolt.WRichTextVerticalAlignTopSafariAndIOS": true,
                                    "specs.thunderbolt.UseWixDataItemService": true,
                                    "specs.thunderbolt.splitLinkUtils": true,
                                    "specs.thunderbolt.UseCloudDataUrlWithBaseExternalUrl": true,
                                    "specs.thunderbolt.popupAriaLabel": true,
                                    "specs.thunderbolt.allowExternalAppsInReact18": true,
                                    "specs.promote.ar.reportEcomPlatformPurchaseEvents": true,
                                    "specs.thunderbolt.useIAMPlatform": true,
                                    "specs.thunderbolt.fiveGridLineStudioSkins": true,
                                    "specs.thunderbolt.TPA3DGalleryEEUrl": true,
                                    "specs.thunderbolt.removeFastlyFetchPolyfill": true,
                                    "specs.thunderbolt.updateLoginSocialBarMenuItemsSDKData": true,
                                    "specs.thunderbolt.moveSentryAboveTheClientHardening": true,
                                    "specs.thunderbolt.carouselGalleryImageFitting": true,
                                    "specs.thunderbolt.dynamicPagesGETfromCSM": true,
                                    "specs.thunderbolt.supportAutoHeightCompsInLandingPage": true,
                                    "specs.thunderbolt.useSvgLoaderFeature": true,
                                    "specs.thunderbolt.pageLayoutFixChrome130": true,
                                    "specs.thunderbolt.loginSocialBarEnableUrlChangeListeners": true,
                                    "specs.thunderbolt.pageTransitionScrollSmoothly": true,
                                    "specs.thunderbolt.buttonUdp_loggedIn": true,
                                    "specs.thunderbolt.InitPlatformApiProvider": true,
                                    "specs.thunderbolt.noHeightOnTextMask": true,
                                    "specs.thunderbolt.allowRoutingBlockerManager": true,
                                    "specs.thunderbolt.LoginBarEnableLoggingInStateInSSR": true,
                                    "specs.thunderbolt.WRichTextVerticalTextNowidth": true,
                                    "specs.thunderbolt.calculateCollapsibleTextLineHeightByFont": true,
                                    "specs.thunderbolt.imageEncodingAVIF": true,
                                    "displayWixAdsNewVersion": true,
                                    "specs.thunderbolt.overflowXClipInMobile": true,
                                    "specs.thunderbolt.dropAppsClientSpecMapByApplicationId": true,
                                    "specs.thunderbolt.BundlerTypescriptListExportedFunctions": true,
                                    "specs.thunderbolt.changeCssMapperDomApplierSelectorToCss": true,
                                    "specs.thunderbolt.smModalsShouldWaitForAppDidMount": true,
                                    "specs.thunderbolt.ooi_css_optimization": true,
                                    "specs.thunderbolt.hardenObject": true,
                                    "specs.thunderbolt.fixGapBelowTextboxonMobileSite": true,
                                    "specs.ShouldForceCaptchaVerificationOnSignupSpec": "Disabled",
                                    "specs.ShouldForceCaptchaVerificationOnLoginSpec": "Disabled",
                                    "specs.thunderbolt.allowSanitizeSvgInSSR": true,
                                    "specs.thunderbolt.css_optimization_change": true,
                                    "specs.thunderbolt.skipLivePreviewRefreshOnSetProps": true,
                                    "specs.thunderbolt.editorElementsRegistryEnsureComponentLoaderFix": true,
                                    "specs.thunderbolt.removeLandingPageClassNameOnUnmount": true,
                                    "specs.thunderbolt.hardenIFrames": true,
                                    "specs.thunderbolt.moveFedopsLoadStartToBody": true,
                                    "specs.thunderbolt.removeSamePageScrollBeforeUnmount": true,
                                    "specs.thunderbolt.shouldFetchLogoutUrlByClientId": true,
                                    "specs.thunderbolt.retainInternalQueryParams": true,
                                    "specs.thunderbolt.passBlocksWidgetBundleUrls": true,
                                    "specs.thunderbolt.convertBirthdateToISOString": true,
                                    "specs.thunderbolt.WixCodeAnalyzeImportedNamespaces": true,
                                    "specs.thunderbolt.getAppTokenForCustomElement": true,
                                    "specs.thunderbolt.send_unused_preloads_to_bi": true,
                                    "specs.thunderbolt.newAuthorizedPagesFlow": true,
                                    "specs.thunderbolt.reportPanelViewerInstanceInitialize": true,
                                    "specs.thunderbolt.fixHasPinnedChildrenRepeaterCalc": true,
                                    "specs.thunderbolt.viewerWithoutWixDynamicCustomElements": true,
                                    "specs.thunderbolt.Panorama": true,
                                    "specs.thunderbolt.hardenTimeout": true,
                                    "specs.thunderbolt.fetchCurrentMemberFromMembersNg": true,
                                    "specs.thunderbolt.logoutOnIAM": true,
                                    "specs.thunderbolt.TextInputAutoFillFix": true,
                                    "specs.thunderbolt.suspenseInSlots": true
                                },
                                "fleetConfig": {
                                    "fleetName": "wix-thunderbolt",
                                    "type": "GA",
                                    "code": 0
                                },
                                "dynamicModelUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/v2\/dynamicmodel",
                                "accessTokensUrl": "https:\/\/aishtapamura.wixsite.com\/author\/_api\/v1\/access-tokens",
                                "rollout": {
                                    "siteAssetsVersionsRollout": false,
                                    "isDACRollout": 0,
                                    "isTBRollout": false
                                },
                                "commonConfig": {
                                    "brand": "wix",
                                    "host": "VIEWER",
                                    "bsi": "",
                                    "consentPolicy": {
                                    },
                                    "consentPolicyHeader": {
                                    },
                                    "siteRevision": "28",
                                    "renderingFlow": "NONE",
                                    "language": "en",
                                    "locale": "es-es"
                                },
                                "componentsLibrariesTopology": [
                                    {
                                        "artifactId": "editor-elements",
                                        "namespace": "wixui",
                                        "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                                    },
                                    {
                                        "artifactId": "editor-elements",
                                        "namespace": "dsgnsys",
                                        "url": "https:\/\/static.parastorage.com\/services\/editor-elements\/1.13447.0"
                                    }
                                ],
                                "anywhereConfig": {
                                },
                                "interactionSampleRatio": 0.01,
                                "rendererType": null,
                                "isPartialRouteMatching": false,
                                "isExcludedFromSecurityExperiments": false,
                                "react18Compatible": true,
                                "react18HydrationBlackListWidgets": [
                                ],
                                "excludeCompsForSSRList": [
                                    ""
                                ]
                            }</script>
                        <script>
                            window.viewerModel = JSON.parse(document.getElementById('wix-viewer-model').textContent)
                        </script>
                        <!-- renderIndicator -->
                        <!-- versionIndicator -->
                        <!-- used platform apis start -->
                        <script type="application/json" id="used-platform-apis-data">
                            [
                            ]</script>
                        <script>
                            window.usedPlatformApis = JSON.parse(document.getElementById('used-platform-apis-data').textContent)
                        </script>
                        <!-- used platform apis end -->
                        <!-- Business Manager -->
                        <!-- initCustomElements #2 -->
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/wixDropdownWrapper.inline.3e467f13.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[1308], {}, p => {
                                p.O(0, [592, 8398], ( () => {
                                    return e = 72757,
                                    p(p.s = e);
                                    var e
                                }
                                ));
                                p.O()
                            }
                            ]);
                        </script>
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/lazyCustomElementWrapper.inline.95017eb5.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[4198], {
                                20826: (e, o, r) => {
                                    r.d(o, {
                                        O: () => s
                                    });
                                    const s = (e, o="") => o.toLowerCase().includes("forcereducedmotion") || Boolean(e?.matchMedia("(prefers-reduced-motion: reduce)").matches)
                                }
                            }, e => {
                                e.O(0, [592, 8398], ( () => {
                                    return o = 98700,
                                    e(e.s = o);
                                    var o
                                }
                                ));
                                e.O()
                            }
                            ]);
                            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/lazyCustomElementWrapper.inline.95017eb5.bundle.min.js.map
                        </script>
                        <!-- initial scripts -->
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/createPlatformWorker.inline.a6c05fb0.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[3169], {
                                11682: (e, t, r) => {
                                    r.r(t),
                                    r.d(t, {
                                        platformWorkerPromise: () => i
                                    });
                                    const {viewerModel: {siteAssets: {clientTopology: s}, siteFeatures: a, siteFeaturesConfigs: {platform: o}, site: {externalBaseUrl: p}}, usedPlatformApis: l} = window
                                      , c = Worker && a.includes("platform")
                                      , i = c ? (async () => {
                                        const e = "platform_create-worker started";
                                        performance.mark(e);
                                        const {clientWorkerUrl: t, appsScripts: r, bootstrapData: a, sdksStaticPaths: c} = o
                                          , {appsSpecData: i, appDefIdToIsMigratedToGetPlatformApi: n, forceEmptySdks: d} = a
                                          , m = t.startsWith("http://localhost:") || t.startsWith("https://bo.wix.com/suricate/") || document.baseURI !== location.href ? (e => {
                                            const t = new Blob([`importScripts('${e}');`],{
                                                type: "application/javascript"
                                            });
                                            return URL.createObjectURL(t)
                                        }
                                        )(t) : t.replace(s.fileRepoUrl, `${p}/_partials`)
                                          , f = new Worker(m)
                                          , u = Object.keys(r.urls).filter((e => !i[e]?.isModuleFederated)).reduce(( (e, t) => (e[t] = r.urls[t],
                                        e)), {});
                                        if (c && c.mainSdks && c.nonMainSdks) {
                                            Object.values(n).every((e => e)) || d ? f.postMessage({
                                                type: "preloadNamespaces",
                                                namespaces: l
                                            }) : f.postMessage({
                                                type: "preloadAllNamespaces",
                                                sdksStaticPaths: c
                                            })
                                        }
                                        f.postMessage({
                                            type: "platformScriptsToPreload",
                                            appScriptsUrls: u
                                        });
                                        const k = "platform_create-worker ended";
                                        return performance.mark(k),
                                        performance.measure("Create Platform Web Worker", e, k),
                                        f
                                    }
                                    )() : Promise.resolve()
                                }
                            }, e => {
                                var t;
                                t = 11682,
                                e(e.s = t)
                            }
                            ]);
                            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/createPlatformWorker.inline.a6c05fb0.bundle.min.js.map
                        </script>
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/windowMessageRegister.inline.2f428192.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[8800], {
                                1643: () => {
                                    !function(e) {
                                        const n = new Set
                                          , a = []
                                          , s = e => {
                                            const a = [];
                                            n.forEach((n => {
                                                e.canHandleEvent(n) && a.push(n)
                                            }
                                            )),
                                            a.forEach((a => {
                                                n.delete(a),
                                                e.handleEvent(a)
                                            }
                                            ))
                                        }
                                        ;
                                        e.addEventListener("message", (e => {
                                            const t = {
                                                source: e.source,
                                                data: e.data,
                                                origin: e.origin
                                            }
                                              , d = a.find((e => e.canHandleEvent(t)));
                                            d ? (s(d),
                                            d.handleEvent(t)) : n.add(t)
                                        }
                                        )),
                                        e._addWindowMessageHandler = e => {
                                            a.push(e),
                                            s(e)
                                        }
                                    }(window)
                                }
                            }, e => {
                                var n;
                                n = 1643,
                                e(e.s = n)
                            }
                            ]);
                            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/windowMessageRegister.inline.2f428192.bundle.min.js.map
                        </script>
                        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/thunderbolt-commons.b6b4e542.bundle.min.js"></script>
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/bi-common.inline.e8c7ad3a.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[507], {
                                27037: (e, t, r) => {
                                    r.d(t, {
                                        h: () => o
                                    });
                                    var s = r(65672);
                                    const a = ({useBatch: e=!0, publishMethod: t=s.PublishMethods.Auto, endpoint: r, muteBi: a=!1, biStore: o, sessionManager: i, fetch: n, factory: p}) => p({
                                        useBatch: e,
                                        publishMethod: t,
                                        endpoint: r
                                    }).setMuted(a).withUoUContext({
                                        msid: o.msid
                                    }).withNonEssentialContext({
                                        visitorId: () => i.getVisitorId(),
                                        siteMemberId: () => i.getSiteMemberId()
                                    }).updateDefaults({
                                        vsi: o.viewerSessionId,
                                        _av: `thunderbolt-${o.viewerVersion}`,
                                        isb: o.is_headless,
                                        ...o.is_headless && {
                                            isbr: o.is_headless_reason
                                        }
                                    })
                                      , o = {
                                        createBaseBiLoggerFactory: a,
                                        createBiLoggerFactoryForFedops: e => {
                                            const {biStore: {session_id: t, initialTimestamp: r, initialRequestTimestamp: s, dc: o, microPop: i, is_headless: n, isCached: p, pageData: d, rolloutData: l, caching: c, checkVisibility: u=( () => ""), viewerVersion: m, requestUrl: h, st: I, isSuccessfulSSR: f}, muteBi: S=!1} = e;
                                            return a({
                                                ...e,
                                                muteBi: S
                                            }).updateDefaults({
                                                ts: () => Date.now() - r,
                                                tsn: () => function({initialRequestTimestamp: e}) {
                                                    return "undefined" == typeof window ? Math.round(performance.now() + (performance.timeOrigin - e)) : Math.round(performance.now())
                                                }({
                                                    initialRequestTimestamp: s
                                                }),
                                                dc: o,
                                                microPop: i,
                                                caching: c,
                                                session_id: t,
                                                st: I,
                                                url: h || d.pageUrl,
                                                ish: n,
                                                pn: d.pageNumber,
                                                isFirstNavigation: 1 === d.pageNumber,
                                                pv: u,
                                                pageId: d.pageId,
                                                isServerSide: !1,
                                                isSuccessfulSSR: f,
                                                is_lightbox: d.isLightbox,
                                                is_cached: p,
                                                is_sav_rollout: l.siteAssetsVersionsRollout ? 1 : 0,
                                                is_dac_rollout: l.isDACRollout ? 1 : 0,
                                                v: m
                                            })
                                        }
                                    }
                                }
                                ,
                                36451: (e, t, r) => {
                                    r.d(t, {
                                        W: () => l
                                    });
                                    var s = r(76022)
                                      , a = r(5189)
                                      , o = r(44029)
                                      , i = r(75967)
                                      , n = r(66715)
                                      , p = r(76904)
                                      , d = r(23184);
                                    const l = ({biLoggerFactory: e, customParams: t={}, phasesConfig: r="SEND_ON_FINISH", appName: l="thunderbolt", presetType: c=s.u.BOLT, reportBlackbox: u=!1, paramsOverrides: m={}, factory: h, muteThunderboltEvents: I=!1, experiments: f={}, monitoringData: S}) => {
                                        const g = h(l, {
                                            presetType: c,
                                            phasesConfig: r,
                                            isPersistent: !0,
                                            isServerSide: !1,
                                            reportBlackbox: u,
                                            customParams: t,
                                            biLoggerFactory: e,
                                            paramsOverrides: m,
                                            enableSampleRateForAppNames: (0,
                                            p.k)("specs.thunderbolt.fedops_enableSampleRateForAppNames", f) ?? ("undefined" != typeof window && (0,
                                            p.k)("specs.thunderbolt.fedops_enableSampleRateForAppNames", f))
                                        })
                                          , {interactionStarted: A, interactionEnded: N, appLoadingPhaseStart: R, appLoadingPhaseFinish: _, appLoadStarted: b, appLoaded: E} = g
                                          , v = (0,
                                        p.k)("specs.thunderbolt.fedopsMuteErrors", f)
                                          , D = (0,
                                        p.k)("specs.thunderbolt.panoramaInSsr", f)
                                          , T = !1
                                          , w = "undefined" == typeof window
                                          , y = e => e.startsWith("platform_")
                                          , O = e => e?.evid && 26 === parseInt(e.evid, 10)
                                          , B = ( () => {
                                            const e = (0,
                                            n.n)();
                                            S?.viewerSessionId && e.setSessionId(S.viewerSessionId);
                                            const r = S?.metaSiteId ?? ""
                                              , s = S?.dc ?? ""
                                              , a = !!S?.isHeadless
                                              , p = !!S?.isCached
                                              , d = !!S?.rolloutData?.isTBRollout
                                              , u = !!S?.rolloutData?.isDACRollout
                                              , m = !!S?.rolloutData?.siteAssetsVersionsRollout;
                                            return (0,
                                            o.V)({
                                                baseParams: {
                                                    platform: i.OD.Viewer,
                                                    msid: r,
                                                    fullArtifactId: "com.wixpress.html-client.wix-thunderbolt",
                                                    componentId: l
                                                },
                                                pluginParams: {
                                                    useBatch: !0
                                                },
                                                data: {
                                                    dataCenter: s,
                                                    isHeadless: a,
                                                    isCached: p,
                                                    isRollout: d,
                                                    isDacRollout: u,
                                                    isSavRollout: m,
                                                    isSsr: T,
                                                    presetType: c,
                                                    customParams: t
                                                },
                                                reporterOptions: w ? {
                                                    fetchFn: fetch
                                                } : {}
                                            }).withGlobalConfig(e).client()
                                        }
                                        )()
                                          , C = e => {
                                            !B || !D && w || (e ? B.reportLoadStart() : B.reportLoadFinish())
                                        }
                                          , P = (e, t, r) => {
                                            if (!B)
                                                return;
                                            const s = e.replaceAll(" ", "_");
                                            t ? B.transaction(s).start(r) : B.transaction(s).finish(r)
                                        }
                                          , V = (e, t, r) => "react-native" !== d.env.RENDERER_BUILD && (O(r) ? v : !( (e, t, r) => {
                                            const o = t?.siteAssetsModule ?? "";
                                            return !(c === s.u.BOLT) || a.EQ.has(e) || r && ["thunderbolt-css", "thunderbolt-features", "thunderbolt-platform"].includes(o)
                                        }
                                        )(e, r, t))
                                          , L = (e, t, r, s) => {
                                            if (a.iy.has(l))
                                                return !0;
                                            if (V(e, t, s))
                                                return !1;
                                            if (s?.siteAssetsModule)
                                                return !0;
                                            const o = !!r?.appId && !a.S_.has(r.appId)
                                              , i = a.S2.has(e)
                                              , n = a.wV.has(e);
                                            return i || o || !n && !I
                                        }
                                        ;
                                        return g.interactionStarted = (e, t) => {
                                            if (O(t?.paramsOverrides) ? ( (e={}) => {
                                                if (!B)
                                                    return;
                                                const {errorInfo: t, errorType: r} = e
                                                  , s = new Error(t);
                                                B?.errorMonitor().reportError(s, {
                                                    errorName: r,
                                                    environment: "Viewer"
                                                })
                                            }
                                            )(t?.paramsOverrides) : (D || y(e) || !w) && P(e, !0),
                                            L(e, !0, void 0, t?.paramsOverrides))
                                                return A.call(g, e, t);
                                            try {
                                                performance.mark(`${e} started`)
                                            } catch {}
                                            return {
                                                timeoutId: 0
                                            }
                                        }
                                        ,
                                        g.interactionEnded = (e, t) => {
                                            if ((D || y(e) || !w) && P(e, !1),
                                            L(e, !0, void 0, t?.paramsOverrides))
                                                N.call(g, e, t);
                                            else
                                                try {
                                                    performance.mark(`${e} ended`)
                                                } catch {}
                                        }
                                        ,
                                        g.appLoadingPhaseStart = (e, t) => {
                                            if (P(e, !0, {
                                                appDefId: t?.appId,
                                                componentId: t?.widgetId
                                            }),
                                            L(e, !1, t))
                                                R.call(g, e, t);
                                            else
                                                try {
                                                    performance.mark(`${e} started`)
                                                } catch {}
                                        }
                                        ,
                                        g.appLoadingPhaseFinish = (e, t, r) => {
                                            if (P(e, !1, {
                                                appDefId: t?.appId,
                                                componentId: t?.widgetId
                                            }),
                                            L(e, !1, t))
                                                _.call(g, e, t, r);
                                            else
                                                try {
                                                    performance.mark(`${e} finished`)
                                                } catch {}
                                        }
                                        ,
                                        g.appLoadStarted = e => {
                                            C(!0),
                                            b.call(g, e)
                                        }
                                        ,
                                        g.appLoaded = e => {
                                            C(!1),
                                            E.call(g, e)
                                        }
                                        ,
                                        g
                                    }
                                }
                                ,
                                58839: (e, t, r) => {
                                    r.d(t, {
                                        c: () => s
                                    });
                                    const s = e => {
                                        const t = "thunderbolt-commons";
                                        return {
                                            reportAsyncWithCustomKey: (r, s, a) => e.reportAsyncWithCustomKey(r, t, s, a),
                                            runAsyncAndReport: (r, s) => e.runAsyncAndReport(r, t, s),
                                            runAndReport: (r, s) => e.runAndReport(r, t, s),
                                            reportError: r => {
                                                e.captureError(r, {
                                                    tags: {
                                                        feature: t,
                                                        clientMetricsReporterError: !0
                                                    }
                                                })
                                            }
                                            ,
                                            meter: (t, r) => {
                                                e.meter(t, r)
                                            }
                                            ,
                                            histogram: (e, t) => {}
                                        }
                                    }
                                }
                                ,
                                97056: (e, t, r) => {
                                    r.r(t),
                                    r.d(t, {
                                        createBiReporter: () => i,
                                        site: () => n
                                    });
                                    var s = r(9492)
                                      , a = r(63590);
                                    const o = (...e) => console.log("[TB] ", ...e);
                                    function i(e=o, t=o, r=( () => {}
                                    ), s=o, a=o) {
                                        return {
                                            reportBI: e,
                                            sendBeat: t,
                                            setDynamicSessionData: r,
                                            reportPageNavigation: s,
                                            reportPageNavigationDone: a
                                        }
                                    }
                                    const n = ({biReporter: e, wixBiSession: t, viewerModel: r}) => o => {
                                        o(s.O$).toConstantValue(t),
                                        o(s.u6).toConstantValue(e),
                                        o(s.lR).toConstantValue((0,
                                        a.f)(r))
                                    }
                                }
                                ,
                                25196: (e, t, r) => {
                                    var s, a;
                                    r.d(t, {
                                        lF: () => s,
                                        mY: () => o,
                                        w4: () => a
                                    }),
                                    function(e) {
                                        e[e.START = 1] = "START",
                                        e[e.VISIBLE = 2] = "VISIBLE",
                                        e[e.PAGE_FINISH = 33] = "PAGE_FINISH",
                                        e[e.FIRST_CDN_RESPONSE = 4] = "FIRST_CDN_RESPONSE",
                                        e[e.TBD = -1] = "TBD",
                                        e[e.PAGE_NAVIGATION = 101] = "PAGE_NAVIGATION",
                                        e[e.PAGE_NAVIGATION_DONE = 103] = "PAGE_NAVIGATION_DONE"
                                    }(s || (s = {})),
                                    function(e) {
                                        e[e.NAVIGATION = 1] = "NAVIGATION",
                                        e[e.DYNAMIC_REDIRECT = 2] = "DYNAMIC_REDIRECT",
                                        e[e.INNER_ROUTE = 3] = "INNER_ROUTE",
                                        e[e.NAVIGATION_ERROR = 4] = "NAVIGATION_ERROR",
                                        e[e.CANCELED = 5] = "CANCELED"
                                    }(a || (a = {}));
                                    const o = {
                                        1: "page-navigation",
                                        2: "page-navigation-redirect",
                                        3: "page-navigation-inner-route",
                                        4: "navigation-error",
                                        5: "navigation-canceled"
                                    }
                                }
                                ,
                                9492: (e, t, r) => {
                                    r.d(t, {
                                        O$: () => a,
                                        lR: () => o,
                                        u6: () => s
                                    });
                                    const s = Symbol.for("BI")
                                      , a = Symbol.for("WixBiSessionSymbol")
                                      , o = Symbol.for("appName")
                                }
                            }]);
                            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/bi-common.inline.e8c7ad3a.bundle.min.js.map
                        </script>
                        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/main.a6252c33.bundle.min.js"></script>
                        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/main.renderer.a20626f8.bundle.min.js"></script>
                        <!-- lodash script -->
                        <script async="" onload="resolveExternalsRegistryModule('lodash')" src="https://static.parastorage.com/unpkg/lodash@4.17.21/lodash.min.js"></script>
                        <!-- react -->
                        <script crossorigin="" onload="resolveExternalsRegistryModule('react')" src="https://static.parastorage.com/unpkg/react@18.3.1/umd/react.production.min.js"></script>
                        <!-- react-dom -->
                        <script crossorigin="" defer="" onload="resolveExternalsRegistryModule('reactDOM')" src="https://static.parastorage.com/unpkg/react-dom@18.3.1/umd/react-dom.production.min.js"></script>
                        <!-- scriptTagsToPreload -->
                        <!-- Old Browsers Deprecation -->
                        <script async="" src="https://static.parastorage.com/services/wix-thunderbolt/dist/browser-deprecation.bundle.es5.js"></script>
                        <!-- bi -->
                        <script>
                            window.clientSideRender = false;
                        </script>
                        <!-- bi -->
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/bi.inline.bee051e0.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[4017], {
                                16992: (e, i, n) => {
                                    n.d(i, {
                                        K: () => m
                                    });
                                    var t = n(25196);
                                    const r = e => {
                                        let i = !1;
                                        if (!/\(iP(hone|ad|od);/i.test(window?.navigator?.userAgent))
                                            try {
                                                i = navigator.sendBeacon(e)
                                            } catch (e) {}
                                        i || ((new Image).src = e)
                                    }
                                      , s = null;
                                    function o([e,i]) {
                                        return i !== s && `${e}=${i}`
                                    }
                                    function a() {
                                        const e = document.cookie.match(/_wixCIDX=([^;]*)/);
                                        return e && e[1]
                                    }
                                    function c(e) {
                                        if (!e)
                                            return s;
                                        const i = new URL(decodeURIComponent(e));
                                        return i.search = "?",
                                        encodeURIComponent(i.href)
                                    }
                                    const d = function(e, {eventType: i, ts: n, tts: t, extra: r=""}, d, l) {
                                        const p = function(e) {
                                            const i = e.split("&").reduce(( (e, i) => {
                                                const [n,t] = i.split("=");
                                                return {
                                                    ...e,
                                                    [n]: t
                                                }
                                            }
                                            ), {});
                                            return (e, n) => void 0 !== i[e] ? i[e] : n
                                        }(r)
                                          , u = (m = d,
                                        e => void 0 === m[e] ? s : m[e]);
                                        var m;
                                        let w = !0;
                                        const f = window?.consentPolicyManager;
                                        if (f) {
                                            const e = f.getCurrentConsentPolicy();
                                            if (e) {
                                                const {policy: i} = e;
                                                w = !(i.functional && i.analytics)
                                            }
                                        }
                                        const g = u("requestUrl")
                                          , h = {
                                            src: "29",
                                            evid: "3",
                                            viewer_name: u("viewerName"),
                                            caching: u("caching"),
                                            client_id: w ? s : a(),
                                            dc: u("dc"),
                                            microPop: u("microPop"),
                                            et: i,
                                            event_name: e ? encodeURIComponent(e) : s,
                                            is_cached: u("isCached"),
                                            is_platform_loaded: u("is_platform_loaded"),
                                            is_rollout: u("is_rollout"),
                                            ism: u("isMesh"),
                                            isp: 0,
                                            isjp: u("isjp"),
                                            iss: u("isServerSide"),
                                            ssr_fb: u("fallbackReason"),
                                            ita: p("ita", d.checkVisibility() ? "1" : "0"),
                                            mid: w ? s : l?.siteMemberId || s,
                                            msid: u("msId"),
                                            pid: p("pid", s),
                                            pn: p("pn", "1"),
                                            ref: document.referrer && !w ? encodeURIComponent(document.referrer) : s,
                                            sar: w ? s : p("sar", screen.availWidth ? `${screen.availWidth}x${screen.availHeight}` : s),
                                            sessionId: w && f ? s : u("sessionId"),
                                            siterev: d.siteRevision || d.siteCacheRevision ? `${d.siteRevision}-${d.siteCacheRevision}` : s,
                                            sr: w ? s : p("sr", screen.width ? `${screen.width}x${screen.height}` : s),
                                            st: u("st"),
                                            ts: n,
                                            tts: t,
                                            url: w ? c(g) : g,
                                            v: window?.thunderboltVersion || "0.0.0",
                                            vid: w ? s : l?.visitorId || s,
                                            bsi: w ? s : l?.bsi || s,
                                            vsi: u("viewerSessionId"),
                                            wor: w || !window.outerWidth ? s : `${window.outerWidth}x${window.outerHeight}`,
                                            wr: w ? s : p("wr", window.innerWidth ? `${window.innerWidth}x${window.innerHeight}` : s),
                                            _brandId: d.commonConfig?.brand || s,
                                            nt: p("nt", s)
                                        };
                                        return `https://frog.wix.com/bt?${Object.entries(h).map(o).filter(Boolean).join("&")}`
                                    }
                                      , l = (e, i) => {
                                        let n, t = "none", r = e.match(/ssr-caching="?cache[,#]\s*desc=([\w-]+)(?:[,#]\s*varnish=(\w+))?(?:[,#]\s*dc[,#]\s*desc=([\w-]+))?(?:"|;|$)/);
                                        if (!r && window.PerformanceServerTiming) {
                                            const e = (e => {
                                                let i, n;
                                                try {
                                                    i = e()
                                                } catch (e) {
                                                    i = []
                                                }
                                                const t = [];
                                                return i.forEach((e => {
                                                    switch (e.name) {
                                                    case "cache":
                                                        t[1] = e.description;
                                                        break;
                                                    case "varnish":
                                                        t[2] = e.description;
                                                        break;
                                                    case "dc":
                                                        n = e.description
                                                    }
                                                }
                                                )),
                                                {
                                                    microPop: n,
                                                    matches: t
                                                }
                                            }
                                            )(i);
                                            n = e.microPop,
                                            r = e.matches
                                        }
                                        if (r && r.length && (t = `${r[1]},${r[2] || "none"}`,
                                        n || (n = r[3])),
                                        "none" === t) {
                                            const e = "undefined" != typeof performance ? performance.timing : null;
                                            e && e.responseStart - e.requestStart == 0 && (t = "browser")
                                        }
                                        return {
                                            caching: t,
                                            isCached: t.includes("hit"),
                                            ...n ? {
                                                microPop: n
                                            } : {}
                                        }
                                    }
                                      , p = {
                                        WixSite: 1,
                                        UGC: 2,
                                        Template: 3
                                    }
                                      , u = () => {
                                        const {fedops: e, viewerModel: {siteFeaturesConfigs: i, requestUrl: n, site: t, fleetConfig: r, commonConfig: s, interactionSampleRatio: o}, clientSideRender: a, santaRenderingError: c} = window
                                          , d = ( ({requestUrl: e, interactionSampleRatio: i}) => {
                                            const n = new URL(e).searchParams;
                                            return n.has("sampleEvents") ? "true" === n.get("sampleEvents") : Math.random() < (i ? 1 - i : .9)
                                        }
                                        )({
                                            requestUrl: n,
                                            interactionSampleRatio: o
                                        })
                                          , u = (e => {
                                            const {userAgent: i} = e.navigator;
                                            return /instagram.+google\/google/i.test(i) ? "" : /bot|google(?!play)|phantom|crawl|spider|headless|slurp|facebookexternal|Lighthouse|PTST|^mozilla\/4\.0$|^\s*$/i.test(i) ? "ua" : ""
                                        }
                                        )(window) || ( () => {
                                            try {
                                                if (window.self === window.top)
                                                    return ""
                                            } catch (e) {}
                                            return "iframe"
                                        }
                                        )() || ( () => {
                                            if (!Function.prototype.bind)
                                                return "bind";
                                            const {document: e, navigator: i} = window;
                                            if (!e || !i)
                                                return "document";
                                            const {webdriver: n, userAgent: t, plugins: r, languages: s} = i;
                                            if (n)
                                                return "webdriver";
                                            if (!r || Array.isArray(r))
                                                return "plugins";
                                            if (Object.getOwnPropertyDescriptor(r, "0")?.writable)
                                                return "plugins-extra";
                                            if (!t)
                                                return "userAgent";
                                            if (t.indexOf("Snapchat") > 0 && e.hidden)
                                                return "Snapchat";
                                            if (!s || 0 === s.length || !Object.isFrozen(s))
                                                return "languages";
                                            try {
                                                throw Error()
                                            } catch (e) {
                                                if (e instanceof Error) {
                                                    const {stack: i} = e;
                                                    if (i && / (\(internal\/)|(\(?file:\/)/.test(i))
                                                        return "stack"
                                                }
                                            }
                                            return ""
                                        }
                                        )() || ( ({seo: e}) => e?.isInSEO ? "seo" : "")(i);
                                        return {
                                            suppressbi: n.includes("suppressbi=true"),
                                            initialTimestamp: window.initialTimestamps.initialTimestamp,
                                            initialRequestTimestamp: window.initialTimestamps.initialRequestTimestamp,
                                            viewerSessionId: e.vsi,
                                            viewerName: t.appNameForBiEvents,
                                            siteRevision: String(t.siteRevision),
                                            msId: t.metaSiteId,
                                            is_rollout: 0 === r.code || 1 === r.code ? r.code : null,
                                            is_platform_loaded: 0,
                                            requestUrl: encodeURIComponent(n),
                                            sessionId: String(t.sessionId),
                                            btype: u,
                                            isjp: !!u,
                                            dc: t.dc,
                                            siteCacheRevision: "__siteCacheRevision__",
                                            checkVisibility: ( () => {
                                                let e = !0;
                                                function i() {
                                                    e = e && !0 !== document.hidden
                                                }
                                                return document.addEventListener("visibilitychange", i, {
                                                    passive: !0
                                                }),
                                                i(),
                                                () => (i(),
                                                e)
                                            }
                                            )(),
                                            ...l(document.cookie, ( () => [...performance.getEntriesByType("navigation")[0].serverTiming || []])),
                                            isMesh: 1,
                                            st: p[t.siteType] || 0,
                                            commonConfig: s,
                                            muteThunderboltEvents: d,
                                            isServerSide: a ? 0 : 1,
                                            isSuccessfulSSR: !a,
                                            fallbackReason: c?.errorInfo
                                        }
                                    }
                                    ;
                                    const m = function() {
                                        const e = u()
                                          , i = {};
                                        let n = 1;
                                        const s = (t, s, o={}) => {
                                            !function(e, i) {
                                                if (i && performance.mark) {
                                                    const n = `${i} (beat ${e})`;
                                                    performance.mark(n)
                                                }
                                            }(t, s);
                                            const a = globalThis.window?.viewerModel;
                                            if (!a?.experiments["specs.thunderbolt.removeSendBeat"]) {
                                                const a = Date.now()
                                                  , c = Math.round(performance.now())
                                                  , l = a - e.initialTimestamp;
                                                if (e.suppressbi || window.__browser_deprecation__)
                                                    return;
                                                const {pageId: p, pageNumber: u=n, navigationType: m} = o;
                                                let w = `&pn=${u}`;
                                                p && (w += `&pid=${p}`),
                                                m && (w += `&nt=${m}`);
                                                const f = d(s, {
                                                    eventType: t,
                                                    ts: l,
                                                    tts: c,
                                                    extra: w
                                                }, e, i);
                                                r(f)
                                            }
                                        }
                                        ;
                                        return {
                                            sendBeat: s,
                                            reportBI: function(e, i) {
                                                !function(e, i) {
                                                    const n = i ? `${e} - ${i}` : e
                                                      , t = "end" === i ? `${e} - start` : null;
                                                    performance.mark(n),
                                                    performance.measure && t && performance.measure(`\u2b50${e}`, t, n)
                                                }(e, i)
                                            },
                                            wixBiSession: e,
                                            sendBeacon: r,
                                            setDynamicSessionData: ({visitorId: e, siteMemberId: n, bsi: t}) => {
                                                i.visitorId = e || i.visitorId,
                                                i.siteMemberId = n || i.siteMemberId,
                                                i.bsi = t || i.bsi
                                            }
                                            ,
                                            reportPageNavigation: function(e) {
                                                n += 1,
                                                s(t.lF.PAGE_NAVIGATION, "page navigation start", {
                                                    pageId: e,
                                                    pageNumber: n
                                                })
                                            },
                                            reportPageNavigationDone: function(e, i) {
                                                s(t.lF.PAGE_NAVIGATION_DONE, "page navigation complete", {
                                                    pageId: e,
                                                    pageNumber: n,
                                                    navigationType: i
                                                }),
                                                i !== t.w4.DYNAMIC_REDIRECT && i !== t.w4.NAVIGATION_ERROR && i !== t.w4.CANCELED || (n -= 1)
                                            }
                                        }
                                    }();
                                    window.bi = m,
                                    window.bi.wixBiSession.isServerSide = window.clientSideRender ? 0 : 1,
                                    window.bi.wixBiSession.isSuccessfulSSR = !window.clientSideRender,
                                    window.clientSideRender && (window.bi.wixBiSession.fallbackReason = window.santaRenderingError?.errorInfo),
                                    m.sendBeat(1, "Init")
                                }
                            }, e => {
                                e.O(0, [507], ( () => {
                                    return i = 16992,
                                    e(e.s = i);
                                    var i
                                }
                                ));
                                e.O()
                            }
                            ]);
                            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/bi.inline.bee051e0.bundle.min.js.map
                        </script>
                        <script data-url="https://static.parastorage.com/services/wix-thunderbolt/dist/sendBeat12.inline.62e7b16d.bundle.min.js">
                            "use strict";
                            (self.webpackJsonp__wix_thunderbolt_app = self.webpackJsonp__wix_thunderbolt_app || []).push([[4017, 7257], {
                                42466: (e, i, n) => {
                                    n(16992).K.sendBeat(12, "Partially visible", {
                                        pageId: window.firstPageId
                                    })
                                }
                                ,
                                16992: (e, i, n) => {
                                    n.d(i, {
                                        K: () => m
                                    });
                                    var t = n(25196);
                                    const r = e => {
                                        let i = !1;
                                        if (!/\(iP(hone|ad|od);/i.test(window?.navigator?.userAgent))
                                            try {
                                                i = navigator.sendBeacon(e)
                                            } catch (e) {}
                                        i || ((new Image).src = e)
                                    }
                                      , s = null;
                                    function o([e,i]) {
                                        return i !== s && `${e}=${i}`
                                    }
                                    function a() {
                                        const e = document.cookie.match(/_wixCIDX=([^;]*)/);
                                        return e && e[1]
                                    }
                                    function c(e) {
                                        if (!e)
                                            return s;
                                        const i = new URL(decodeURIComponent(e));
                                        return i.search = "?",
                                        encodeURIComponent(i.href)
                                    }
                                    const d = function(e, {eventType: i, ts: n, tts: t, extra: r=""}, d, l) {
                                        const p = function(e) {
                                            const i = e.split("&").reduce(( (e, i) => {
                                                const [n,t] = i.split("=");
                                                return {
                                                    ...e,
                                                    [n]: t
                                                }
                                            }
                                            ), {});
                                            return (e, n) => void 0 !== i[e] ? i[e] : n
                                        }(r)
                                          , u = (m = d,
                                        e => void 0 === m[e] ? s : m[e]);
                                        var m;
                                        let w = !0;
                                        const f = window?.consentPolicyManager;
                                        if (f) {
                                            const e = f.getCurrentConsentPolicy();
                                            if (e) {
                                                const {policy: i} = e;
                                                w = !(i.functional && i.analytics)
                                            }
                                        }
                                        const g = u("requestUrl")
                                          , h = {
                                            src: "29",
                                            evid: "3",
                                            viewer_name: u("viewerName"),
                                            caching: u("caching"),
                                            client_id: w ? s : a(),
                                            dc: u("dc"),
                                            microPop: u("microPop"),
                                            et: i,
                                            event_name: e ? encodeURIComponent(e) : s,
                                            is_cached: u("isCached"),
                                            is_platform_loaded: u("is_platform_loaded"),
                                            is_rollout: u("is_rollout"),
                                            ism: u("isMesh"),
                                            isp: 0,
                                            isjp: u("isjp"),
                                            iss: u("isServerSide"),
                                            ssr_fb: u("fallbackReason"),
                                            ita: p("ita", d.checkVisibility() ? "1" : "0"),
                                            mid: w ? s : l?.siteMemberId || s,
                                            msid: u("msId"),
                                            pid: p("pid", s),
                                            pn: p("pn", "1"),
                                            ref: document.referrer && !w ? encodeURIComponent(document.referrer) : s,
                                            sar: w ? s : p("sar", screen.availWidth ? `${screen.availWidth}x${screen.availHeight}` : s),
                                            sessionId: w && f ? s : u("sessionId"),
                                            siterev: d.siteRevision || d.siteCacheRevision ? `${d.siteRevision}-${d.siteCacheRevision}` : s,
                                            sr: w ? s : p("sr", screen.width ? `${screen.width}x${screen.height}` : s),
                                            st: u("st"),
                                            ts: n,
                                            tts: t,
                                            url: w ? c(g) : g,
                                            v: window?.thunderboltVersion || "0.0.0",
                                            vid: w ? s : l?.visitorId || s,
                                            bsi: w ? s : l?.bsi || s,
                                            vsi: u("viewerSessionId"),
                                            wor: w || !window.outerWidth ? s : `${window.outerWidth}x${window.outerHeight}`,
                                            wr: w ? s : p("wr", window.innerWidth ? `${window.innerWidth}x${window.innerHeight}` : s),
                                            _brandId: d.commonConfig?.brand || s,
                                            nt: p("nt", s)
                                        };
                                        return `https://frog.wix.com/bt?${Object.entries(h).map(o).filter(Boolean).join("&")}`
                                    }
                                      , l = (e, i) => {
                                        let n, t = "none", r = e.match(/ssr-caching="?cache[,#]\s*desc=([\w-]+)(?:[,#]\s*varnish=(\w+))?(?:[,#]\s*dc[,#]\s*desc=([\w-]+))?(?:"|;|$)/);
                                        if (!r && window.PerformanceServerTiming) {
                                            const e = (e => {
                                                let i, n;
                                                try {
                                                    i = e()
                                                } catch (e) {
                                                    i = []
                                                }
                                                const t = [];
                                                return i.forEach((e => {
                                                    switch (e.name) {
                                                    case "cache":
                                                        t[1] = e.description;
                                                        break;
                                                    case "varnish":
                                                        t[2] = e.description;
                                                        break;
                                                    case "dc":
                                                        n = e.description
                                                    }
                                                }
                                                )),
                                                {
                                                    microPop: n,
                                                    matches: t
                                                }
                                            }
                                            )(i);
                                            n = e.microPop,
                                            r = e.matches
                                        }
                                        if (r && r.length && (t = `${r[1]},${r[2] || "none"}`,
                                        n || (n = r[3])),
                                        "none" === t) {
                                            const e = "undefined" != typeof performance ? performance.timing : null;
                                            e && e.responseStart - e.requestStart == 0 && (t = "browser")
                                        }
                                        return {
                                            caching: t,
                                            isCached: t.includes("hit"),
                                            ...n ? {
                                                microPop: n
                                            } : {}
                                        }
                                    }
                                      , p = {
                                        WixSite: 1,
                                        UGC: 2,
                                        Template: 3
                                    }
                                      , u = () => {
                                        const {fedops: e, viewerModel: {siteFeaturesConfigs: i, requestUrl: n, site: t, fleetConfig: r, commonConfig: s, interactionSampleRatio: o}, clientSideRender: a, santaRenderingError: c} = window
                                          , d = ( ({requestUrl: e, interactionSampleRatio: i}) => {
                                            const n = new URL(e).searchParams;
                                            return n.has("sampleEvents") ? "true" === n.get("sampleEvents") : Math.random() < (i ? 1 - i : .9)
                                        }
                                        )({
                                            requestUrl: n,
                                            interactionSampleRatio: o
                                        })
                                          , u = (e => {
                                            const {userAgent: i} = e.navigator;
                                            return /instagram.+google\/google/i.test(i) ? "" : /bot|google(?!play)|phantom|crawl|spider|headless|slurp|facebookexternal|Lighthouse|PTST|^mozilla\/4\.0$|^\s*$/i.test(i) ? "ua" : ""
                                        }
                                        )(window) || ( () => {
                                            try {
                                                if (window.self === window.top)
                                                    return ""
                                            } catch (e) {}
                                            return "iframe"
                                        }
                                        )() || ( () => {
                                            if (!Function.prototype.bind)
                                                return "bind";
                                            const {document: e, navigator: i} = window;
                                            if (!e || !i)
                                                return "document";
                                            const {webdriver: n, userAgent: t, plugins: r, languages: s} = i;
                                            if (n)
                                                return "webdriver";
                                            if (!r || Array.isArray(r))
                                                return "plugins";
                                            if (Object.getOwnPropertyDescriptor(r, "0")?.writable)
                                                return "plugins-extra";
                                            if (!t)
                                                return "userAgent";
                                            if (t.indexOf("Snapchat") > 0 && e.hidden)
                                                return "Snapchat";
                                            if (!s || 0 === s.length || !Object.isFrozen(s))
                                                return "languages";
                                            try {
                                                throw Error()
                                            } catch (e) {
                                                if (e instanceof Error) {
                                                    const {stack: i} = e;
                                                    if (i && / (\(internal\/)|(\(?file:\/)/.test(i))
                                                        return "stack"
                                                }
                                            }
                                            return ""
                                        }
                                        )() || ( ({seo: e}) => e?.isInSEO ? "seo" : "")(i);
                                        return {
                                            suppressbi: n.includes("suppressbi=true"),
                                            initialTimestamp: window.initialTimestamps.initialTimestamp,
                                            initialRequestTimestamp: window.initialTimestamps.initialRequestTimestamp,
                                            viewerSessionId: e.vsi,
                                            viewerName: t.appNameForBiEvents,
                                            siteRevision: String(t.siteRevision),
                                            msId: t.metaSiteId,
                                            is_rollout: 0 === r.code || 1 === r.code ? r.code : null,
                                            is_platform_loaded: 0,
                                            requestUrl: encodeURIComponent(n),
                                            sessionId: String(t.sessionId),
                                            btype: u,
                                            isjp: !!u,
                                            dc: t.dc,
                                            siteCacheRevision: "__siteCacheRevision__",
                                            checkVisibility: ( () => {
                                                let e = !0;
                                                function i() {
                                                    e = e && !0 !== document.hidden
                                                }
                                                return document.addEventListener("visibilitychange", i, {
                                                    passive: !0
                                                }),
                                                i(),
                                                () => (i(),
                                                e)
                                            }
                                            )(),
                                            ...l(document.cookie, ( () => [...performance.getEntriesByType("navigation")[0].serverTiming || []])),
                                            isMesh: 1,
                                            st: p[t.siteType] || 0,
                                            commonConfig: s,
                                            muteThunderboltEvents: d,
                                            isServerSide: a ? 0 : 1,
                                            isSuccessfulSSR: !a,
                                            fallbackReason: c?.errorInfo
                                        }
                                    }
                                    ;
                                    const m = function() {
                                        const e = u()
                                          , i = {};
                                        let n = 1;
                                        const s = (t, s, o={}) => {
                                            !function(e, i) {
                                                if (i && performance.mark) {
                                                    const n = `${i} (beat ${e})`;
                                                    performance.mark(n)
                                                }
                                            }(t, s);
                                            const a = globalThis.window?.viewerModel;
                                            if (!a?.experiments["specs.thunderbolt.removeSendBeat"]) {
                                                const a = Date.now()
                                                  , c = Math.round(performance.now())
                                                  , l = a - e.initialTimestamp;
                                                if (e.suppressbi || window.__browser_deprecation__)
                                                    return;
                                                const {pageId: p, pageNumber: u=n, navigationType: m} = o;
                                                let w = `&pn=${u}`;
                                                p && (w += `&pid=${p}`),
                                                m && (w += `&nt=${m}`);
                                                const f = d(s, {
                                                    eventType: t,
                                                    ts: l,
                                                    tts: c,
                                                    extra: w
                                                }, e, i);
                                                r(f)
                                            }
                                        }
                                        ;
                                        return {
                                            sendBeat: s,
                                            reportBI: function(e, i) {
                                                !function(e, i) {
                                                    const n = i ? `${e} - ${i}` : e
                                                      , t = "end" === i ? `${e} - start` : null;
                                                    performance.mark(n),
                                                    performance.measure && t && performance.measure(`\u2b50${e}`, t, n)
                                                }(e, i)
                                            },
                                            wixBiSession: e,
                                            sendBeacon: r,
                                            setDynamicSessionData: ({visitorId: e, siteMemberId: n, bsi: t}) => {
                                                i.visitorId = e || i.visitorId,
                                                i.siteMemberId = n || i.siteMemberId,
                                                i.bsi = t || i.bsi
                                            }
                                            ,
                                            reportPageNavigation: function(e) {
                                                n += 1,
                                                s(t.lF.PAGE_NAVIGATION, "page navigation start", {
                                                    pageId: e,
                                                    pageNumber: n
                                                })
                                            },
                                            reportPageNavigationDone: function(e, i) {
                                                s(t.lF.PAGE_NAVIGATION_DONE, "page navigation complete", {
                                                    pageId: e,
                                                    pageNumber: n,
                                                    navigationType: i
                                                }),
                                                i !== t.w4.DYNAMIC_REDIRECT && i !== t.w4.NAVIGATION_ERROR && i !== t.w4.CANCELED || (n -= 1)
                                            }
                                        }
                                    }();
                                    window.bi = m,
                                    window.bi.wixBiSession.isServerSide = window.clientSideRender ? 0 : 1,
                                    window.bi.wixBiSession.isSuccessfulSSR = !window.clientSideRender,
                                    window.clientSideRender && (window.bi.wixBiSession.fallbackReason = window.santaRenderingError?.errorInfo),
                                    m.sendBeat(1, "Init")
                                }
                            }, e => {
                                e.O(0, [507], ( () => {
                                    return i = 42466,
                                    e(e.s = i);
                                    var i
                                }
                                ));
                                e.O()
                            }
                            ]);
                            //# sourceMappingURL=https://static.parastorage.com/services/wix-thunderbolt/dist/sendBeat12.inline.62e7b16d.bundle.min.js.map
                        </script>
                        <script>
                            window.firstPageId = 'c1dmp'

                            if (window.requestCloseWelcomeScreen) {
                                window.requestCloseWelcomeScreen()
                            }
                            if (!window.__browser_deprecation__) {
                                window.fedops.phaseStarted('partially_visible', {
                                    paramsOverrides: {
                                        pageId: firstPageId,
                                        isSuccessfulSSR: !clientSideRender
                                    }
                                })
                            }
                        </script>
                        <script defer="" src="https://static.parastorage.com/services/tag-manager-client/1.920.0/siteTags.bundle.min.js"></script>
                        <!--pageHtmlEmbeds.bodyEnd start-->
                        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyEnd start"></script>
                        <script type="wix/htmlEmbeds" id="pageHtmlEmbeds.bodyEnd end"></script>
                        <!--pageHtmlEmbeds.bodyEnd end-->
                        <!-- warmup data start -->
                        <script type="application/json" id="wix-warmup-data">
                            {
                                "platform": {
                                    "ssrPropsUpdates": [
                                    ],
                                    "ssrStyleUpdates": [
                                    ],
                                    "ssrStructureUpdates": [
                                    ]
                                },
                                "pages": {
                                    "compIdToTypeMap": {
                                        "comp-kjcp8qvu": "FiveGridLine",
                                        "comp-kjcoigli": "VectorImage",
                                        "comp-kjcog6xb": "WRichText",
                                        "comp-kjcohe65": "WRichText",
                                        "comp-kj9sx3ul": "DropDownMenu",
                                        "comp-kjcp7mwn": "WRichText",
                                        "comp-kj9u7gc8": "WRichText",
                                        "comp-kjcp7w67": "WRichText",
                                        "comp-kj9u7jfm": "WRichText",
                                        "comp-kjcp5ldh": "WRichText",
                                        "comp-kjcp46jj": "LinkBar",
                                        "comp-kjcktbxp": "WRichText",
                                        "masterPage": "MasterPage",
                                        "SITE_HEADER": "HeaderContainer",
                                        "PAGES_CONTAINER": "PagesContainer",
                                        "SITE_FOOTER": "FooterContainer",
                                        "comp-kj9svnyb": "StripColumnsContainer",
                                        "SITE_PAGES": "PageGroup",
                                        "comp-kj9u5y5z": "StripColumnsContainer",
                                        "comp-kj9svo67": "Column",
                                        "comp-kj9sw3na": "Column",
                                        "comp-kj9u5ybj": "Column",
                                        "comp-kj9u6b1a": "Column",
                                        "comp-kj9u6e6n": "Column",
                                        "comp-kjcktbwb": "Column",
                                        "BACKGROUND_GROUP": "BackgroundGroup",
                                        "WIX_ADS": "FreemiumBannerDesktop",
                                        "SCROLL_TO_TOP": "Anchor",
                                        "SCROLL_TO_BOTTOM": "Anchor",
                                        "SKIP_TO_CONTENT_BTN": "SkipToContentButton",
                                        "comp-kjcl52y9": "WPhoto",
                                        "comp-kj9sumrm": "WRichText",
                                        "comp-kj9u78b4": "WRichText",
                                        "comp-kjcod4ll": "SiteButton",
                                        "comp-kjcod5ul": "SiteButton",
                                        "comp-kjcocqs6": "SiteButton",
                                        "pageBackground_c1dmp": "PageBackground",
                                        "c1dmp": "Page",
                                        "comp-lslo8zdk": "ClassicSection",
                                        "Containerc1dmp": "Group",
                                        "DYNAMIC_STRUCTURE_CONTAINER": "DynamicStructureContainer",
                                        "site-root": "DivWithChildren",
                                        "main_MF": "DivWithChildren",
                                        "c1dmp_wrapper": "PageMountUnmount",
                                        "c1dmp_wrapper_background": "PageMountUnmount"
                                    }
                                },
                                "appsWarmupData": {
                                },
                                "ooi": {
                                    "failedInSsr": {
                                    }
                                }
                            }</script>
                        <!-- warmup data end -->
                    </body>
                </html>

