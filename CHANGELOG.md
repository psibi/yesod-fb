# Version 0.5.0

* Change type signature of `fbHttpManager` from `site -> Manager` to `(Y.MonadHandler m, Y.HandlerSite m ~ site) => m HTTP.Manager`.
* Default method definition for `fbHttpManager` added.
* Lower bounds added for conduit, http-conduit etc.
