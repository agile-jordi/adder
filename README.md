`adder` demonstrates the basics of developing and deploying a Clojure web application. The [associated blog post](http://mmcgrana.github.com/2010/07/develop-deploy-clojure-web-applications.html) walks through the rationale and details.

After the post was written some changes have been made to keep the example up to the current versions of Clojure, Compojure, Ring and Hiccup:

- Migrate the usage of hiccup.page-helpers to hiccup.page (the new example renders an HTML5 page)
- Explicitly add (wrap-params)
- Move the run script to src

Now the example can be run using:

	lein run -m script.run