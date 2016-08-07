+++
date = "2016-06-11T14:43:49+01:00"
draft = false
title = "Updating Third Party Packages in Go"
type = "post"
+++

Just a short post on how to update packages using *go get*.

To update all third party packages in your *GOPATH* use the following command:

> go get -u all

To update a specific package, just provide the full package name to *go get*:

> go get -u github.com/gorilla/mux

What about vendor-ed packages? These are updated in exactly the same way as above:

> go get -u my-project/vendor/megacorp/foo

If you want more information about your *GOPATH*, run the command:

> go help gopath

Fin.
