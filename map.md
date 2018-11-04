<!DOCTYPE html>
<head>    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    <script>L_PREFER_CANVAS=false; L_NO_TOUCH=false; L_DISABLE_3D=false;</script>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/js/bootstrap.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.2.0/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.2.0/css/bootstrap-theme.min.css"/>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://rawgit.com/python-visualization/folium/master/folium/templates/leaflet.awesome.rotate.css"/>
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    
    <style>#map_c51bf55af33145a9a333b284115cf2b8 {
        position: relative;
        width: 100.0%;
        height: 100.0%;
        left: 0.0%;
        top: 0.0%;
        }
    </style>
</head>
<body>    
    
    <div class="folium-map" id="map_c51bf55af33145a9a333b284115cf2b8" ></div>
</body>
<script>    
    
    
        var bounds = null;
    

    var map_c51bf55af33145a9a333b284115cf2b8 = L.map(
        'map_c51bf55af33145a9a333b284115cf2b8', {
        center: [48.5132, 32.2597],
        zoom: 13,
        maxBounds: bounds,
        layers: [],
        worldCopyJump: false,
        crs: L.CRS.EPSG3857,
        zoomControl: true,
        });

    
    
    var tile_layer_4897aac95f7f40848f29449b5e87257f = L.tileLayer(
        'https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png',
        {
        "attribution": null,
        "detectRetina": false,
        "maxNativeZoom": 18,
        "maxZoom": 18,
        "minZoom": 0,
        "noWrap": false,
        "subdomains": "abc"
}).addTo(map_c51bf55af33145a9a333b284115cf2b8);
    
            var circle_marker_071480566a554954b009f2d8e4a0028a = L.circleMarker(
                [48.50555555555555, 32.251666666666665],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "cyan",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_6e16907e9a574cb595f8ae945d4d883b = L.popup({maxWidth: '300'
            
            });

            
                var html_46bdcf720a084b518bd0448765cdbe58 = $('<div id="html_46bdcf720a084b518bd0448765cdbe58" style="width: 100.0%; height: 100.0%;">Кировоградский городской литературно-мемориальный музей И. К. Карпенко-Карого, Кропивницкий (Кировоград)</div>')[0];
                popup_6e16907e9a574cb595f8ae945d4d883b.setContent(html_46bdcf720a084b518bd0448765cdbe58);
            

            circle_marker_071480566a554954b009f2d8e4a0028a.bindPopup(popup_6e16907e9a574cb595f8ae945d4d883b)
            ;

            
        
    
            var circle_marker_4d5de081ebbd450fa33f5347c6873537 = L.circleMarker(
                [48.50888888888889, 32.268055555555556],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_5f8c8f0bd6f04082a9459ac9c8aa93a4 = L.popup({maxWidth: '300'
            
            });

            
                var html_f6266c0943c94eba84444afe19d42f7d = $('<div id="html_f6266c0943c94eba84444afe19d42f7d" style="width: 100.0%; height: 100.0%;">Кировоградский городской музей музыкальной культуры им. Кароля Шимановского, Кропивницкий (Кировоград)</div>')[0];
                popup_5f8c8f0bd6f04082a9459ac9c8aa93a4.setContent(html_f6266c0943c94eba84444afe19d42f7d);
            

            circle_marker_4d5de081ebbd450fa33f5347c6873537.bindPopup(popup_5f8c8f0bd6f04082a9459ac9c8aa93a4)
            ;

            
        
    
            var circle_marker_5671a89bf4fd4a7c88f6795548388f85 = L.circleMarker(
                [48.50972222222222, 32.26888888888889],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_a1909be4528e4d8bbb1b780c41fe49f2 = L.popup({maxWidth: '300'
            
            });

            
                var html_e23aafecdba54ab1b4638e25c008a0cc = $('<div id="html_e23aafecdba54ab1b4638e25c008a0cc" style="width: 100.0%; height: 100.0%;">Кировоградский областной краеведческий музей, Кропивницкий (Кировоград)</div>')[0];
                popup_a1909be4528e4d8bbb1b780c41fe49f2.setContent(html_e23aafecdba54ab1b4638e25c008a0cc);
            

            circle_marker_5671a89bf4fd4a7c88f6795548388f85.bindPopup(popup_a1909be4528e4d8bbb1b780c41fe49f2)
            ;

            
        
    
            var circle_marker_0f001cdc94e14081aacea60ccf235739 = L.circleMarker(
                [48.505833333333335, 32.26305555555555],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_688a42319d0c4d5db308f0ed0cf64709 = L.popup({maxWidth: '300'
            
            });

            
                var html_688c2fc2190e47bd92f3fafaf0d001c1 = $('<div id="html_688c2fc2190e47bd92f3fafaf0d001c1" style="width: 100.0%; height: 100.0%;">Кировоградский областной художественный музей , Кропивницкий (Кировоград)</div>')[0];
                popup_688a42319d0c4d5db308f0ed0cf64709.setContent(html_688c2fc2190e47bd92f3fafaf0d001c1);
            

            circle_marker_0f001cdc94e14081aacea60ccf235739.bindPopup(popup_688a42319d0c4d5db308f0ed0cf64709)
            ;

            
        
    
            var circle_marker_9c7706b165914b01b9b741778380cfb6 = L.circleMarker(
                [48.506388888888885, 32.27722222222222],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_9b67301034254df0975b92335e1ba049 = L.popup({maxWidth: '300'
            
            });

            
                var html_f9f10fbf45aa42abb3b68d43d0594460 = $('<div id="html_f9f10fbf45aa42abb3b68d43d0594460" style="width: 100.0%; height: 100.0%;">Кировоградский художественно-мемориальный музей художника А. А. Осмеркина, Кропивницкий (Кировоград)</div>')[0];
                popup_9b67301034254df0975b92335e1ba049.setContent(html_f9f10fbf45aa42abb3b68d43d0594460);
            

            circle_marker_9c7706b165914b01b9b741778380cfb6.bindPopup(popup_9b67301034254df0975b92335e1ba049)
            ;

            
        
    
            var circle_marker_a07c405b237d4100b99b5ec84956bc52 = L.circleMarker(
                [48.5, 32.271388888888886],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_c7078dca704c4a73b6b7595cdbf254e7 = L.popup({maxWidth: '300'
            
            });

            
                var html_c875f9b7e5594c5eaccb096b4797ced6 = $('<div id="html_c875f9b7e5594c5eaccb096b4797ced6" style="width: 100.0%; height: 100.0%;">Мемориальный музей М.Л. Кропивницкого, Кропивницкий (Кировоград)</div>')[0];
                popup_c7078dca704c4a73b6b7595cdbf254e7.setContent(html_c875f9b7e5594c5eaccb096b4797ced6);
            

            circle_marker_a07c405b237d4100b99b5ec84956bc52.bindPopup(popup_c7078dca704c4a73b6b7595cdbf254e7)
            ;

            
        
    
            var circle_marker_ac28a92605af44bab3a228199e995078 = L.circleMarker(
                [48.50888888888889, 32.268055555555556],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_601e2a20ccfe474a97622568f2739254 = L.popup({maxWidth: '300'
            
            });

            
                var html_2a952c6e9da842abb2a108fbee988229 = $('<div id="html_2a952c6e9da842abb2a108fbee988229" style="width: 100.0%; height: 100.0%;">Народный музей Г. Нейгауза, Кропивницкий (Кировоград)</div>')[0];
                popup_601e2a20ccfe474a97622568f2739254.setContent(html_2a952c6e9da842abb2a108fbee988229);
            

            circle_marker_ac28a92605af44bab3a228199e995078.bindPopup(popup_601e2a20ccfe474a97622568f2739254)
            ;

            
        
    
            var circle_marker_e39b0643e0be404b8cb3163a0a44a187 = L.circleMarker(
                [48.52916666666667, 32.26166666666666],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_ff69887d11504f9faf743f8003ad9b99 = L.popup({maxWidth: '300'
            
            });

            
                var html_1ff322b61ae24e4b90ff618e7779d1a2 = $('<div id="html_1ff322b61ae24e4b90ff618e7779d1a2" style="width: 100.0%; height: 100.0%;">Храм Успения Пресвятой Богородицы, Кропивницкий (Кировоград)</div>')[0];
                popup_ff69887d11504f9faf743f8003ad9b99.setContent(html_1ff322b61ae24e4b90ff618e7779d1a2);
            

            circle_marker_e39b0643e0be404b8cb3163a0a44a187.bindPopup(popup_ff69887d11504f9faf743f8003ad9b99)
            ;

            
        
    
            var circle_marker_2150c4ad12684ae191f0dd8a5601ed15 = L.circleMarker(
                [48.509166666666665, 32.26861111111111],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_1d139b9b904c42de88adb2039a1d9162 = L.popup({maxWidth: '300'
            
            });

            
                var html_7b6a10886e1047fca1370a3f343e2cb7 = $('<div id="html_7b6a10886e1047fca1370a3f343e2cb7" style="width: 100.0%; height: 100.0%;">Галерея Елисаветград, Кропивницкий (Кировоград)</div>')[0];
                popup_1d139b9b904c42de88adb2039a1d9162.setContent(html_7b6a10886e1047fca1370a3f343e2cb7);
            

            circle_marker_2150c4ad12684ae191f0dd8a5601ed15.bindPopup(popup_1d139b9b904c42de88adb2039a1d9162)
            ;

            
        
    
            var circle_marker_1b193b6995ef4682a14342e96e029ce9 = L.circleMarker(
                [48.5075, 32.26111111111111],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_f8f46c6e099a4f6482c33a48e28d4eae = L.popup({maxWidth: '300'
            
            });

            
                var html_b3fe021d59af468c9eda031c803972bc = $('<div id="html_b3fe021d59af468c9eda031c803972bc" style="width: 100.0%; height: 100.0%;">Кировоградский академический областной театр кукол, Кропивницкий (Кировоград)</div>')[0];
                popup_f8f46c6e099a4f6482c33a48e28d4eae.setContent(html_b3fe021d59af468c9eda031c803972bc);
            

            circle_marker_1b193b6995ef4682a14342e96e029ce9.bindPopup(popup_f8f46c6e099a4f6482c33a48e28d4eae)
            ;

            
        
    
            var circle_marker_e41109493aad454a851d09a72998157e = L.circleMarker(
                [48.51361111111111, 32.25833333333333],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_2c1e5df8cb444132b26c2103f8372ed6 = L.popup({maxWidth: '300'
            
            });

            
                var html_cf46d6b1194d45328be981c8178f422f = $('<div id="html_cf46d6b1194d45328be981c8178f422f" style="width: 100.0%; height: 100.0%;">Кировоградский областной украинский музыкально-драматический театр имени М. Кропивницкого, Кропивницкий (Кировоград)</div>')[0];
                popup_2c1e5df8cb444132b26c2103f8372ed6.setContent(html_cf46d6b1194d45328be981c8178f422f);
            

            circle_marker_e41109493aad454a851d09a72998157e.bindPopup(popup_2c1e5df8cb444132b26c2103f8372ed6)
            ;

            
        
    
            var circle_marker_0d63aa549bd54b988989780247988bbd = L.circleMarker(
                [48.507777777777775, 32.26583333333333],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_086cecfba15a4ca6a066acf703e72650 = L.popup({maxWidth: '300'
            
            });

            
                var html_f9f0344cfc2c49b495182a26a1ae1ca9 = $('<div id="html_f9f0344cfc2c49b495182a26a1ae1ca9" style="width: 100.0%; height: 100.0%;">Монумент Стрела Амура, Кропивницкий (Кировоград)</div>')[0];
                popup_086cecfba15a4ca6a066acf703e72650.setContent(html_f9f0344cfc2c49b495182a26a1ae1ca9);
            

            circle_marker_0d63aa549bd54b988989780247988bbd.bindPopup(popup_086cecfba15a4ca6a066acf703e72650)
            ;

            
        
    
            var circle_marker_3983b1e11fce41fcab6092d8d1f5c975 = L.circleMarker(
                [48.50833333333333, 32.26555555555556],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_8c78f544149b49c497b4d2556290b2fb = L.popup({maxWidth: '300'
            
            });

            
                var html_598e1a05e9d845c595ddad6db368b869 = $('<div id="html_598e1a05e9d845c595ddad6db368b869" style="width: 100.0%; height: 100.0%;">Памятник А.Пашутину , Кропивницкий (Кировоград)</div>')[0];
                popup_8c78f544149b49c497b4d2556290b2fb.setContent(html_598e1a05e9d845c595ddad6db368b869);
            

            circle_marker_3983b1e11fce41fcab6092d8d1f5c975.bindPopup(popup_8c78f544149b49c497b4d2556290b2fb)
            ;

            
        
    
            var circle_marker_8fcd579b61824968b67bb47e610b8007 = L.circleMarker(
                [48.51833333333333, 32.27472222222222],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "magenta",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_39fdc17361b74412bef9766c3c6541e8 = L.popup({maxWidth: '300'
            
            });

            
                var html_3ae469686c78421f85cba5acf7e6b0a5 = $('<div id="html_3ae469686c78421f85cba5acf7e6b0a5" style="width: 100.0%; height: 100.0%;">Памятник Ангел-хранитель Украины, Кропивницкий (Кировоград)</div>')[0];
                popup_39fdc17361b74412bef9766c3c6541e8.setContent(html_3ae469686c78421f85cba5acf7e6b0a5);
            

            circle_marker_8fcd579b61824968b67bb47e610b8007.bindPopup(popup_39fdc17361b74412bef9766c3c6541e8)
            ;

            
        
    
            var circle_marker_d1dc470d08f44c3db588a0b2c5c9f8f8 = L.circleMarker(
                [48.514722222222225, 32.26138888888889],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_42f0d65591364e0c83edc6530ff9f10c = L.popup({maxWidth: '300'
            
            });

            
                var html_5984a3be3c554b85abd19f7d478fcff5 = $('<div id="html_5984a3be3c554b85abd19f7d478fcff5" style="width: 100.0%; height: 100.0%;">Памятник В. Винниченко , Кропивницкий (Кировоград)</div>')[0];
                popup_42f0d65591364e0c83edc6530ff9f10c.setContent(html_5984a3be3c554b85abd19f7d478fcff5);
            

            circle_marker_d1dc470d08f44c3db588a0b2c5c9f8f8.bindPopup(popup_42f0d65591364e0c83edc6530ff9f10c)
            ;

            
        
    
            var circle_marker_9ff88938fde6444897d863437eeedbb3 = L.circleMarker(
                [48.51833333333333, 32.27861111111111],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "magenta",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_26bbc97ddb804ee98e8f48414f4ee08c = L.popup({maxWidth: '300'
            
            });

            
                var html_3a8abf20fe3647ebbc9241b0046b2d4c = $('<div id="html_3a8abf20fe3647ebbc9241b0046b2d4c" style="width: 100.0%; height: 100.0%;">Памятник Г. Нейгаузу , Кропивницкий (Кировоград)</div>')[0];
                popup_26bbc97ddb804ee98e8f48414f4ee08c.setContent(html_3a8abf20fe3647ebbc9241b0046b2d4c);
            

            circle_marker_9ff88938fde6444897d863437eeedbb3.bindPopup(popup_26bbc97ddb804ee98e8f48414f4ee08c)
            ;

            
        
    
            var circle_marker_f97648da3f7e4107a5e57389ee04935f = L.circleMarker(
                [48.507777777777775, 32.264722222222225],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_439f92631e0842e8a02fd6a31d6da5e4 = L.popup({maxWidth: '300'
            
            });

            
                var html_fb952cb00c7347a1b962076686f011cf = $('<div id="html_fb952cb00c7347a1b962076686f011cf" style="width: 100.0%; height: 100.0%;">Памятник ДворникЪ, Кропивницкий (Кировоград)</div>')[0];
                popup_439f92631e0842e8a02fd6a31d6da5e4.setContent(html_fb952cb00c7347a1b962076686f011cf);
            

            circle_marker_f97648da3f7e4107a5e57389ee04935f.bindPopup(popup_439f92631e0842e8a02fd6a31d6da5e4)
            ;

            
        
    
            var circle_marker_e2b6694b43074b97ace015911ba17aeb = L.circleMarker(
                [48.49722222222222, 32.23111111111111],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_ed0cbcb4cc174bf7a267198354a5b85b = L.popup({maxWidth: '300'
            
            });

            
                var html_466cbdd4054642359373263a1b34154a = $('<div id="html_466cbdd4054642359373263a1b34154a" style="width: 100.0%; height: 100.0%;">Памятник И. Тамму, Кропивницкий (Кировоград)</div>')[0];
                popup_ed0cbcb4cc174bf7a267198354a5b85b.setContent(html_466cbdd4054642359373263a1b34154a);
            

            circle_marker_e2b6694b43074b97ace015911ba17aeb.bindPopup(popup_ed0cbcb4cc174bf7a267198354a5b85b)
            ;

            
        
    
            var circle_marker_af9befc7d9f14840bb376ada88138b5e = L.circleMarker(
                [48.51416666666667, 32.25888888888889],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_338b95ec4ec04d01acfd3f3791f6a50c = L.popup({maxWidth: '300'
            
            });

            
                var html_0402215fb79b42879feed80f3fb0a948 = $('<div id="html_0402215fb79b42879feed80f3fb0a948" style="width: 100.0%; height: 100.0%;">Памятник М. Кропивницкому , Кропивницкий (Кировоград)</div>')[0];
                popup_338b95ec4ec04d01acfd3f3791f6a50c.setContent(html_0402215fb79b42879feed80f3fb0a948);
            

            circle_marker_af9befc7d9f14840bb376ada88138b5e.bindPopup(popup_338b95ec4ec04d01acfd3f3791f6a50c)
            ;

            
        
    
            var circle_marker_8b2788bfcc7f4721b3c4f85f412decce = L.circleMarker(
                [48.4975, 32.25361111111111],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "cyan",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_03a2d5f8b3b44b318c1e5ef178ba0383 = L.popup({maxWidth: '300'
            
            });

            
                var html_a745517f59f743b483f9576fcca514e5 = $('<div id="html_a745517f59f743b483f9576fcca514e5" style="width: 100.0%; height: 100.0%;">Памятник Н. Пирогову , Кропивницкий (Кировоград)</div>')[0];
                popup_03a2d5f8b3b44b318c1e5ef178ba0383.setContent(html_a745517f59f743b483f9576fcca514e5);
            

            circle_marker_8b2788bfcc7f4721b3c4f85f412decce.bindPopup(popup_03a2d5f8b3b44b318c1e5ef178ba0383)
            ;

            
        
    
            var circle_marker_debd21cc6b9641e5b9a366148b8cc161 = L.circleMarker(
                [48.51277777777778, 32.2625],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_551a2bbfd8174462981c32c24f249c67 = L.popup({maxWidth: '300'
            
            });

            
                var html_a09f6e3424894abcb5632e444c775ed8 = $('<div id="html_a09f6e3424894abcb5632e444c775ed8" style="width: 100.0%; height: 100.0%;">Памятник первому трамваю г. Елисаветград, Кропивницкий (Кировоград)</div>')[0];
                popup_551a2bbfd8174462981c32c24f249c67.setContent(html_a09f6e3424894abcb5632e444c775ed8);
            

            circle_marker_debd21cc6b9641e5b9a366148b8cc161.bindPopup(popup_551a2bbfd8174462981c32c24f249c67)
            ;

            
        
    
            var circle_marker_593130b565c74036b7943b6569b91b6d = L.circleMarker(
                [48.51111111111111, 32.269999999999996],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_93f984d74c964a0987a9256874940978 = L.popup({maxWidth: '300'
            
            });

            
                var html_5bd46c4987b640b6a6dc890708a39dca = $('<div id="html_5bd46c4987b640b6a6dc890708a39dca" style="width: 100.0%; height: 100.0%;">Памятник Птица счастья Стрекоза, Кропивницкий (Кировоград)</div>')[0];
                popup_93f984d74c964a0987a9256874940978.setContent(html_5bd46c4987b640b6a6dc890708a39dca);
            

            circle_marker_593130b565c74036b7943b6569b91b6d.bindPopup(popup_93f984d74c964a0987a9256874940978)
            ;

            
        
    
            var circle_marker_267cb6b5c16f45c79b3771e3799208fd = L.circleMarker(
                [48.52027777777778, 32.263888888888886],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_9bec0a33f09e4999b16ad5ab6fc17fad = L.popup({maxWidth: '300'
            
            });

            
                var html_461e6f6bfc0d48dc98e3130897d34749 = $('<div id="html_461e6f6bfc0d48dc98e3130897d34749" style="width: 100.0%; height: 100.0%;">Памятник Роберту и Томасу Эльворти, Кропивницкий (Кировоград)</div>')[0];
                popup_9bec0a33f09e4999b16ad5ab6fc17fad.setContent(html_461e6f6bfc0d48dc98e3130897d34749);
            

            circle_marker_267cb6b5c16f45c79b3771e3799208fd.bindPopup(popup_9bec0a33f09e4999b16ad5ab6fc17fad)
            ;

            
        
    
            var circle_marker_850aa864f9b94b8e8fdae73654d82f71 = L.circleMarker(
                [48.49805555555556, 32.251666666666665],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "cyan",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_d09b7d530103468b8bed3dfcbaf07e6e = L.popup({maxWidth: '300'
            
            });

            
                var html_cad25996926f4f0089a8fa431935a147 = $('<div id="html_cad25996926f4f0089a8fa431935a147" style="width: 100.0%; height: 100.0%;">Памятник Скорбящая Родина-мать, Кропивницкий (Кировоград)</div>')[0];
                popup_d09b7d530103468b8bed3dfcbaf07e6e.setContent(html_cad25996926f4f0089a8fa431935a147);
            

            circle_marker_850aa864f9b94b8e8fdae73654d82f71.bindPopup(popup_d09b7d530103468b8bed3dfcbaf07e6e)
            ;

            
        
    
            var circle_marker_1c6579ad3341495c8424d8513d634a35 = L.circleMarker(
                [48.52722222222222, 32.291666666666664],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "magenta",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_bec62114a7d94a7489a3ac33b785c492 = L.popup({maxWidth: '300'
            
            });

            
                var html_cebb32f9ff284633a7c5a8157141031f = $('<div id="html_cebb32f9ff284633a7c5a8157141031f" style="width: 100.0%; height: 100.0%;">Памятник советским артиллеристам, Кропивницкий (Кировоград)</div>')[0];
                popup_bec62114a7d94a7489a3ac33b785c492.setContent(html_cebb32f9ff284633a7c5a8157141031f);
            

            circle_marker_1c6579ad3341495c8424d8513d634a35.bindPopup(popup_bec62114a7d94a7489a3ac33b785c492)
            ;

            
        
    
            var circle_marker_2bddeed8dd634c8891c4af8c874ba753 = L.circleMarker(
                [48.50555555555555, 32.21388888888889],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_dd852da76efb48e3b0b8fad44c0838a3 = L.popup({maxWidth: '300'
            
            });

            
                var html_676a46ab40074b95a461e3cc77677623 = $('<div id="html_676a46ab40074b95a461e3cc77677623" style="width: 100.0%; height: 100.0%;">Памятник студентам, Кропивницкий (Кировоград)</div>')[0];
                popup_dd852da76efb48e3b0b8fad44c0838a3.setContent(html_676a46ab40074b95a461e3cc77677623);
            

            circle_marker_2bddeed8dd634c8891c4af8c874ba753.bindPopup(popup_dd852da76efb48e3b0b8fad44c0838a3)
            ;

            
        
    
            var circle_marker_f4867c6fca504bc1ab1279bcc6b5fd99 = L.circleMarker(
                [48.51888888888889, 32.2725],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "magenta",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_d2ef67efd6f44a44abbb5d6572f0c80f = L.popup({maxWidth: '300'
            
            });

            
                var html_2b637556ebac4304a4d625e00205b85a = $('<div id="html_2b637556ebac4304a4d625e00205b85a" style="width: 100.0%; height: 100.0%;">Памятник Трудовой Славы-сеялки СЗ-36 и Россия, Кропивницкий (Кировоград)</div>')[0];
                popup_d2ef67efd6f44a44abbb5d6572f0c80f.setContent(html_2b637556ebac4304a4d625e00205b85a);
            

            circle_marker_f4867c6fca504bc1ab1279bcc6b5fd99.bindPopup(popup_d2ef67efd6f44a44abbb5d6572f0c80f)
            ;

            
        
    
            var circle_marker_80ffd0d52d174ac3b21e9d56cd1e13e2 = L.circleMarker(
                [48.513888888888886, 32.25972222222222],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_4e4226dc9dad45af900020cec30bd03e = L.popup({maxWidth: '300'
            
            });

            
                var html_61b746237f994612875a85a706352104 = $('<div id="html_61b746237f994612875a85a706352104" style="width: 100.0%; height: 100.0%;">Памятник-фонтан Наталка Полтавка, Кропивницкий (Кировоград)</div>')[0];
                popup_4e4226dc9dad45af900020cec30bd03e.setContent(html_61b746237f994612875a85a706352104);
            

            circle_marker_80ffd0d52d174ac3b21e9d56cd1e13e2.bindPopup(popup_4e4226dc9dad45af900020cec30bd03e)
            ;

            
        
    
            var circle_marker_2f45b28032394514b8150b2a4c953502 = L.circleMarker(
                [48.50472222222222, 32.268055555555556],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_96a9b9eeb93e4200827f257b6b2c0d8a = L.popup({maxWidth: '300'
            
            });

            
                var html_1803a9a08c954561adcb44a15e0816af = $('<div id="html_1803a9a08c954561adcb44a15e0816af" style="width: 100.0%; height: 100.0%;">Памятный знак в честь 2000-летия Рождества Христова, Кропивницкий (Кировоград)</div>')[0];
                popup_96a9b9eeb93e4200827f257b6b2c0d8a.setContent(html_1803a9a08c954561adcb44a15e0816af);
            

            circle_marker_2f45b28032394514b8150b2a4c953502.bindPopup(popup_96a9b9eeb93e4200827f257b6b2c0d8a)
            ;

            
        
    
            var circle_marker_1db353fc4ef94226a8d469af5125509f = L.circleMarker(
                [48.5025, 32.25944444444445],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "cyan",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_6395f0afe596446cb353c37ac60d3c1c = L.popup({maxWidth: '300'
            
            });

            
                var html_8251dc16ce3f47b1b875bcdd4891db78 = $('<div id="html_8251dc16ce3f47b1b875bcdd4891db78" style="width: 100.0%; height: 100.0%;">Памятный знак в честь святой Елисавети, Кропивницкий (Кировоград)</div>')[0];
                popup_6395f0afe596446cb353c37ac60d3c1c.setContent(html_8251dc16ce3f47b1b875bcdd4891db78);
            

            circle_marker_1db353fc4ef94226a8d469af5125509f.bindPopup(popup_6395f0afe596446cb353c37ac60d3c1c)
            ;

            
        
    
            var circle_marker_183634b12c8d4f918fc5ab400d4965a0 = L.circleMarker(
                [48.51027777777778, 32.26888888888889],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_d4fa803815ac45b58c5580126461dab8 = L.popup({maxWidth: '300'
            
            });

            
                var html_6860e19eaf5a4cb092054668d3b58722 = $('<div id="html_6860e19eaf5a4cb092054668d3b58722" style="width: 100.0%; height: 100.0%;">Скульптурная группа Пантеры, Кропивницкий (Кировоград)</div>')[0];
                popup_d4fa803815ac45b58c5580126461dab8.setContent(html_6860e19eaf5a4cb092054668d3b58722);
            

            circle_marker_183634b12c8d4f918fc5ab400d4965a0.bindPopup(popup_d4fa803815ac45b58c5580126461dab8)
            ;

            
        
    
            var circle_marker_e9339c02dd03407db86c9769f71bb8e1 = L.circleMarker(
                [48.50861111111111, 32.26777777777777],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_f417774d5de148fc992eb3a12f3e6caf = L.popup({maxWidth: '300'
            
            });

            
                var html_1f46f14dba6e496cae950942449d4326 = $('<div id="html_1f46f14dba6e496cae950942449d4326" style="width: 100.0%; height: 100.0%;">Главная синагога, Кропивницкий (Кировоград)</div>')[0];
                popup_f417774d5de148fc992eb3a12f3e6caf.setContent(html_1f46f14dba6e496cae950942449d4326);
            

            circle_marker_e9339c02dd03407db86c9769f71bb8e1.bindPopup(popup_f417774d5de148fc992eb3a12f3e6caf)
            ;

            
        
    
            var circle_marker_f4f00428a32443839f44a8a70a524f2e = L.circleMarker(
                [48.50416666666667, 32.260555555555555],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_03a1df8557bd4fbfa1217a975188166b = L.popup({maxWidth: '300'
            
            });

            
                var html_312c608736d84809bedce2394fc13b68 = $('<div id="html_312c608736d84809bedce2394fc13b68" style="width: 100.0%; height: 100.0%;">Греческая церковь, Кропивницкий (Кировоград)</div>')[0];
                popup_03a1df8557bd4fbfa1217a975188166b.setContent(html_312c608736d84809bedce2394fc13b68);
            

            circle_marker_f4f00428a32443839f44a8a70a524f2e.bindPopup(popup_03a1df8557bd4fbfa1217a975188166b)
            ;

            
        
    
            var circle_marker_d387e6fa0ab34baea36eb6c9a0251a53 = L.circleMarker(
                [48.499722222222225, 32.231388888888894],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "blue",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_2fc2f0151ac74d62bc9b091a0886dcde = L.popup({maxWidth: '300'
            
            });

            
                var html_0ee70c4f6860486c9423e7761cc5734b = $('<div id="html_0ee70c4f6860486c9423e7761cc5734b" style="width: 100.0%; height: 100.0%;">Дендропарк в Кировограде, Кропивницкий (Кировоград)</div>')[0];
                popup_2fc2f0151ac74d62bc9b091a0886dcde.setContent(html_0ee70c4f6860486c9423e7761cc5734b);
            

            circle_marker_d387e6fa0ab34baea36eb6c9a0251a53.bindPopup(popup_2fc2f0151ac74d62bc9b091a0886dcde)
            ;

            
        
    
            var circle_marker_3226aee6b2a14842a8389e54f884af19 = L.circleMarker(
                [48.51583333333333, 32.25861111111111],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_e8ee03b4967b48a89f8f3fb53e67e667 = L.popup({maxWidth: '300'
            
            });

            
                var html_0bfd3ab910dd44cc8012eede195d8151 = $('<div id="html_0bfd3ab910dd44cc8012eede195d8151" style="width: 100.0%; height: 100.0%;">Ковалевский парк, Кропивницкий (Кировоград)</div>')[0];
                popup_e8ee03b4967b48a89f8f3fb53e67e667.setContent(html_0bfd3ab910dd44cc8012eede195d8151);
            

            circle_marker_3226aee6b2a14842a8389e54f884af19.bindPopup(popup_e8ee03b4967b48a89f8f3fb53e67e667)
            ;

            
        
    
            var circle_marker_d5c71a8a6df44c53853a1da4fba4945e = L.circleMarker(
                [48.498333333333335, 32.254444444444445],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "cyan",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_f2f8217646bc43a5ba0b3ebcbb2ce1aa = L.popup({maxWidth: '300'
            
            });

            
                var html_0aaab2e2efc644768181699e389b03a6 = $('<div id="html_0aaab2e2efc644768181699e389b03a6" style="width: 100.0%; height: 100.0%;">Крепость Святой Елизаветы, Кропивницкий (Кировоград)</div>')[0];
                popup_f2f8217646bc43a5ba0b3ebcbb2ce1aa.setContent(html_0aaab2e2efc644768181699e389b03a6);
            

            circle_marker_d5c71a8a6df44c53853a1da4fba4945e.bindPopup(popup_f2f8217646bc43a5ba0b3ebcbb2ce1aa)
            ;

            
        
    
            var circle_marker_1624a4e6fb244a8b8112bf1705360095 = L.circleMarker(
                [48.51583333333333, 32.26138888888889],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_9ead8300971948ab903ba3f1cf097b60 = L.popup({maxWidth: '300'
            
            });

            
                var html_fcad68a97f77460f8051e2e4a0f07c4e = $('<div id="html_fcad68a97f77460f8051e2e4a0f07c4e" style="width: 100.0%; height: 100.0%;">Крепость Юнкерское училище, Кропивницкий (Кировоград)</div>')[0];
                popup_9ead8300971948ab903ba3f1cf097b60.setContent(html_fcad68a97f77460f8051e2e4a0f07c4e);
            

            circle_marker_1624a4e6fb244a8b8112bf1705360095.bindPopup(popup_9ead8300971948ab903ba3f1cf097b60)
            ;

            
        
    
            var circle_marker_cb7c042969d648868dc9d8f3669f13c7 = L.circleMarker(
                [48.51722222222222, 32.26],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_ac9bb3a7c5264f13a46b95add1ded95e = L.popup({maxWidth: '300'
            
            });

            
                var html_33f07e32be01484c8d4fb0aa2c0258d4 = $('<div id="html_33f07e32be01484c8d4fb0aa2c0258d4" style="width: 100.0%; height: 100.0%;">Областная филармония, Кропивницкий (Кировоград)</div>')[0];
                popup_ac9bb3a7c5264f13a46b95add1ded95e.setContent(html_33f07e32be01484c8d4fb0aa2c0258d4);
            

            circle_marker_cb7c042969d648868dc9d8f3669f13c7.bindPopup(popup_ac9bb3a7c5264f13a46b95add1ded95e)
            ;

            
        
    
            var circle_marker_7ae8b2eba8bc471ba77124bff7a000f5 = L.circleMarker(
                [48.52861111111111, 32.265],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_447424dbdf2d4c2ea8e1468470c1627d = L.popup({maxWidth: '300'
            
            });

            
                var html_5bffaac772e64bc4aaae1b36d15f3f74 = $('<div id="html_5bffaac772e64bc4aaae1b36d15f3f74" style="width: 100.0%; height: 100.0%;">Парк имени Крючкова, Кропивницкий (Кировоград)</div>')[0];
                popup_447424dbdf2d4c2ea8e1468470c1627d.setContent(html_5bffaac772e64bc4aaae1b36d15f3f74);
            

            circle_marker_7ae8b2eba8bc471ba77124bff7a000f5.bindPopup(popup_447424dbdf2d4c2ea8e1468470c1627d)
            ;

            
        
    
            var circle_marker_0e7abc172e354a998ff32be6cd17c02d = L.circleMarker(
                [48.48277777777778, 32.25833333333333],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "cyan",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_5d734f491fe640c2b26293f188ac0f44 = L.popup({maxWidth: '300'
            
            });

            
                var html_1243dd648bf44a0db64a360d936be59b = $('<div id="html_1243dd648bf44a0db64a360d936be59b" style="width: 100.0%; height: 100.0%;">Парк Победы (Горсад), Кропивницкий (Кировоград)</div>')[0];
                popup_5d734f491fe640c2b26293f188ac0f44.setContent(html_1243dd648bf44a0db64a360d936be59b);
            

            circle_marker_0e7abc172e354a998ff32be6cd17c02d.bindPopup(popup_5d734f491fe640c2b26293f188ac0f44)
            ;

            
        
    
            var circle_marker_3a3bebd75f204530887121a36ec850cf = L.circleMarker(
                [48.51722222222222, 32.255833333333335],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "yellow",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_9e587f601ba34d6c88c50d7ec7df8c6b = L.popup({maxWidth: '300'
            
            });

            
                var html_3e1705ec27594e9ea65b93cddaea6014 = $('<div id="html_3e1705ec27594e9ea65b93cddaea6014" style="width: 100.0%; height: 100.0%;">Покровская церковь, Кропивницкий (Кировоград)</div>')[0];
                popup_9e587f601ba34d6c88c50d7ec7df8c6b.setContent(html_3e1705ec27594e9ea65b93cddaea6014);
            

            circle_marker_3a3bebd75f204530887121a36ec850cf.bindPopup(popup_9e587f601ba34d6c88c50d7ec7df8c6b)
            ;

            
        
    
            var circle_marker_bdf37e1f07d34e42b34744e819374959 = L.circleMarker(
                [48.50472222222222, 32.26833333333333],
                {
  "bubblingMouseEvents": true,
  "color": "#3388ff",
  "dashArray": null,
  "dashOffset": null,
  "fill": true,
  "fillColor": "red",
  "fillOpacity": 0.7,
  "fillRule": "evenodd",
  "lineCap": "round",
  "lineJoin": "round",
  "opacity": 1.0,
  "radius": 10,
  "stroke": true,
  "weight": 3
}
                )
                .addTo(map_c51bf55af33145a9a333b284115cf2b8);
            
    
            var popup_a564f37406584e02a8f3a7380f5c7347 = L.popup({maxWidth: '300'
            
            });

            
                var html_efe9f2a498254f6787d6fb954b142464 = $('<div id="html_efe9f2a498254f6787d6fb954b142464" style="width: 100.0%; height: 100.0%;">Спасо-преображенский собор, Кропивницкий (Кировоград)</div>')[0];
                popup_a564f37406584e02a8f3a7380f5c7347.setContent(html_efe9f2a498254f6787d6fb954b142464);
            

            circle_marker_bdf37e1f07d34e42b34744e819374959.bindPopup(popup_a564f37406584e02a8f3a7380f5c7347)
            ;

            
        
</script>