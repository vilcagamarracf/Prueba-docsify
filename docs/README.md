# Nested Sidebars

You may want the sidebar to update with only navigation to reflect the current directory. This can be done by adding a _sidebar.md file to each folder.

_sidebar.md is loaded from each level directory. If the current directory doesn't have _sidebar.md, it will fall back to the parent directory. If, for example, the current path is /guide/quick-start, the _sidebar.md will be loaded from /guide/_sidebar.md.

You can specify alias to avoid unnecessary fallback.