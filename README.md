# essp (ECMAScript Server Pages)

"essp" is a module for parsing and rendering server side javascript pages.  This core module is somewhat abstract to enable it to be implemented on many different platforms.  A number of wrapper modules are included to enable easy out-of-the-virtual-box use.

Wrapper modules currently provided for Node and V8+essp-server.  A few more are planned including one for common-nix rapsberry.

Installation (coming soon) via npm:

  `npm install essp --save`

Rendering usage (from node):

  `essp index.essp --output-dir=./build`
  
    or
      
  `essp --self-contained index.essp >index.html`

Internal server usage (from node, see the essp-server project):

  `essp-server`
 
    or
    
  `essp-server --doc-root=./public --address=127.0.0.1 --port=8080`

For more information and FAQs, see: http://laughingsun.github.io/essp

For API documentation, see: ./docs/api/index.md.

For information on other platforms, see: ./platforms/readme.md.
