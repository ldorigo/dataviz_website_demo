---
title: "Bokeh"
date: 2021-03-16T11:21:51+01:00
draft: true
---


# A fantastic Bokeh plot



<script type="text/javascript" src="https://cdn.bokeh.org/bokeh/release/bokeh-2.3.0.min.js" integrity="sha384-HjagQp6T0/7bxYTAXbLotF1MLAGWmhkY5siA1Gc/pcEgvgRPtMsRn0gQtMwGKiw1" crossorigin="anonymous"></script>
<script type="text/javascript">
            Bokeh.set_log_level("info");
</script>
<div class="bk-root" id="1044757f-41aa-4b32-bb9f-06b12ec084fd" data-root-id="1002">
</div>
<script type="application/json" id="1148">
          {"89261226-eaca-4e2d-9ce8-f19d280be23e":{"defs":[{"extends":null,"module":null,"name":"DataModel","overrides":[],"properties":[]}],"roots":{"references":[{"attributes":{"source":{"id":"1033"}},"id":"1037","type":"CDSView"},{"attributes":{"bottom_units":"screen","fill_alpha":0.5,"fill_color":"lightgrey","left_units":"screen","level":"overlay","line_alpha":1.0,"line_color":"black","line_dash":[4,4],"line_width":2,"right_units":"screen","syncable":false,"top_units":"screen"},"id":"1025","type":"BoxAnnotation"},{"attributes":{},"id":"1048","type":"UnionRenderers"},{"attributes":{},"id":"1043","type":"BasicTickFormatter"},{"attributes":{"below":[{"id":"1011"}],"center":[{"id":"1014"},{"id":"1018"}],"left":[{"id":"1015"}],"renderers":[{"id":"1036"}],"title":{"id":"1039"},"toolbar":{"id":"1026"},"x_range":{"id":"1003"},"x_scale":{"id":"1007"},"y_range":{"id":"1005"},"y_scale":{"id":"1009"}},"id":"1002","subtype":"Figure","type":"Plot"},{"attributes":{},"id":"1024","type":"HelpTool"},{"attributes":{"active_multi":null,"tools":[{"id":"1019"},{"id":"1020"},{"id":"1021"},{"id":"1022"},{"id":"1023"},{"id":"1024"}]},"id":"1026","type":"Toolbar"},{"attributes":{"formatter":{"id":"1040"},"major_label_policy":{"id":"1042"},"ticker":{"id":"1016"}},"id":"1015","type":"LinearAxis"},{"attributes":{},"id":"1045","type":"AllLabels"},{"attributes":{"data":{"x":[1,2],"y":[3,4]},"selected":{"id":"1047"},"selection_policy":{"id":"1048"}},"id":"1033","type":"ColumnDataSource"},{"attributes":{"axis":{"id":"1015"},"dimension":1,"ticker":null},"id":"1018","type":"Grid"},{"attributes":{},"id":"1042","type":"AllLabels"},{"attributes":{},"id":"1016","type":"BasicTicker"},{"attributes":{"fill_alpha":{"value":0.1},"fill_color":{"value":"#1f77b4"},"line_alpha":{"value":0.1},"line_color":{"value":"#1f77b4"},"x":{"field":"x"},"y":{"field":"y"}},"id":"1035","type":"Circle"},{"attributes":{},"id":"1012","type":"BasicTicker"},{"attributes":{},"id":"1040","type":"BasicTickFormatter"},{"attributes":{},"id":"1020","type":"WheelZoomTool"},{"attributes":{},"id":"1009","type":"LinearScale"},{"attributes":{},"id":"1039","type":"Title"},{"attributes":{},"id":"1019","type":"PanTool"},{"attributes":{},"id":"1005","type":"DataRange1d"},{"attributes":{"data_source":{"id":"1033"},"glyph":{"id":"1034"},"hover_glyph":null,"muted_glyph":null,"nonselection_glyph":{"id":"1035"},"view":{"id":"1037"}},"id":"1036","type":"GlyphRenderer"},{"attributes":{"overlay":{"id":"1025"}},"id":"1021","type":"BoxZoomTool"},{"attributes":{},"id":"1007","type":"LinearScale"},{"attributes":{"axis":{"id":"1011"},"ticker":null},"id":"1014","type":"Grid"},{"attributes":{},"id":"1003","type":"DataRange1d"},{"attributes":{},"id":"1022","type":"SaveTool"},{"attributes":{},"id":"1023","type":"ResetTool"},{"attributes":{"fill_color":{"value":"#1f77b4"},"line_color":{"value":"#1f77b4"},"x":{"field":"x"},"y":{"field":"y"}},"id":"1034","type":"Circle"},{"attributes":{"formatter":{"id":"1043"},"major_label_policy":{"id":"1045"},"ticker":{"id":"1012"}},"id":"1011","type":"LinearAxis"},{"attributes":{},"id":"1047","type":"Selection"}],"root_ids":["1002"]},"title":"Bokeh Application","version":"2.3.0"}}
        </script>
        <script type="text/javascript">
          (function() {
            var fn = function() {
              Bokeh.safely(function() {
                (function(root) {
                  function embed_document(root) {
                  var docs_json = document.getElementById('1148').textContent;
                  var render_items = [{"docid":"89261226-eaca-4e2d-9ce8-f19d280be23e","root_ids":["1002"],"roots":{"1002":"1044757f-41aa-4b32-bb9f-06b12ec084fd"}}];
                  root.Bokeh.embed.embed_items(docs_json, render_items);
                  }
                  if (root.Bokeh !== undefined) {
                    embed_document(root);
                  } else {
                    var attempts = 0;
                    var timer = setInterval(function(root) {
                      if (root.Bokeh !== undefined) {
                        clearInterval(timer);
                        embed_document(root);
                      } else {
                        attempts++;
                        if (attempts > 100) {
                          clearInterval(timer);
                          console.log("Bokeh: ERROR: Unable to run BokehJS code because BokehJS library is missing");
                        }
                      }
                    }, 10, root)
                  }
                })(window);
              });
            };
            if (document.readyState != "loading") fn();
            else document.addEventListener("DOMContentLoaded", fn);
          })();
        </script>
