# Glossary - Quickstart DjangoRestFramework

Serializers

> A serializer is an object responsible for transforming a Model or Collection that's returned from your route handlers into a JSON payload that's formatted the way your frontend app expects. *


Viewsets

> Rather than write multiple views we're grouping together all the common behavior into classes called ViewSets.

> We can easily break these down into individual views if we need to, but using viewsets keeps the view logic nicely organized as well as being very concise.

Routers

> Because we're using viewsets instead of views, we can automatically generate the URL conf for our API, by simply registering the viewsets with a router class.

> If we need more control over the API URLs we can simply drop down to using regular class-based views, and writing the URL conf explicitly.

Pagination

> REST framework includes support for customizable pagination styles. This allows you to modify how large result sets are split into individual pages of data.

* Taken from [Miragejs](https://miragejs.com/docs/main-concepts/serializers/)

Nearly all taken from [Miragejs](https://miragejs.com/docs/main-concepts/serializers/)
