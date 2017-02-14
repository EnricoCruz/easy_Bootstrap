## __Bootstrap fast anotations__
---

* NavBar:
_class=_ "navbar" \\ navbar-default\\inverse || navbar-fixed-top|bottom
 * div _class=_ "container"
    * div _class=_ "navbar-header"
       * button _class=_ "navbar-toggle", "data-toggle='collapse', data-target='#myNavbar'
       * div _class=_ "navbar-brand"
   * ul _class=_ "nav" || navbar-nav  (child of div.collapse navbar-collapse && #myNavbar :to make collapsable list)
      * li _class=_ "active"
      * li _class=_ "dropdown" (to make a dropdown list inside)
        * ul _class=_ "dropdown-menu"
          * li(X)
        
  * ul _class=_ "nav" || navbar-nav || navbar-right -->
