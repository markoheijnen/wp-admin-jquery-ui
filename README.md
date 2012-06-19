WP Admin jQuery UI
=========================

As proposed in Trac ticket [#18909](http://core.trac.wordpress.org/ticket/18909), there should be some sort of matching CSS for the WordPress admin now that all jQuery UI components are bundled. While decisions would have to be made about how these are bundled, if at all, this is at least a start to having [a] matching stylesheet[s] for the WordPress admin and jQuery UI.

This is a plugin that will create a jQuery UI demo page under the Tools menu. Color scheme will change based on the user's setting. Scripts and stylesheets are enqueued on the demo screen only.



Marko Heijnen
=========================
Removed all the current css stuff WordPress adds now.

Deregistered editor-buttons and registered an own version of it for testing purpose.
Deregistered wp-jquery-ui-dialog since it is duplicated with the css in editor-buttons


Other Notes
=========================

Removed margin #wp-link #link-options and changed top padding to 0 so only bottom has a padding of 14px.
