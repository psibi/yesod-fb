# Version 0.5.3

* Restrict base version

# Version 0.5.2

* Fix MonadFail issue

# Version 0.5.1

* Remove crypto-api dependency and move over to memory package
* Have MonadFail constraint

# Version 0.5.0

* Change type signature of `fbHttpManager` from `site -> Manager` to `(Y.MonadHandler m, Y.HandlerSite m ~ site) => m HTTP.Manager`.
* Default method definition for `fbHttpManager` added.
* Lower bounds added for conduit, http-conduit etc.
