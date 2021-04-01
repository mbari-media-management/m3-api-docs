<script src="https://unpkg.com/swagger-ui-dist@3/swagger-ui-bundle.js" charset="UTF-8"></script>
<script>
var SwaggerUIBundle = require('swagger-ui-dist').SwaggerUIBundle

const ui = SwaggerUIBundle({
    url: "https://raw.githubusercontent.com/mbari-media-management/m3-api-docs/main/reference/vars-kb-server.v1.yaml",
    dom_id: 'swagger-ui',
    presets: [
      SwaggerUIBundle.presets.apis,
      SwaggerUIBundle.SwaggerUIStandalonePreset
    ],
    layout: "StandaloneLayout"
  })
</script>

# M3 API Documentation

Trying this out
<div id="swagger-ui">Hello</div>
