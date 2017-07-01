<!-- Tufts VUE 3.3.0 concept-map (FSMs.vue) 2017-07-01 -->
<!-- Tufts VUE: http://vue.tufts.edu/ -->
<!-- Do Not Remove: VUE mapping @version(1.1) jar:file:/C:/Program%20Files%20(x86)/VUE/VUE.jar!/tufts/vue/resources/lw_mapping_1_1.xml -->
<!-- Do Not Remove: Saved date Sat Jul 01 22:10:58 CEST 2017 by dries on platform Windows 8 6.2 in JVM 1.7.0_21-b11 -->
<!-- Do Not Remove: Saving version @(#)VUE: built October 8 2015 at 1658 by tomadm on Linux 2.6.32-504.23.4.el6.x86_64 i386 JVM 1.7.0_21-b11(bits=32) -->
<?xml version="1.0" encoding="US-ASCII"?>
<LW-MAP xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:noNamespaceSchemaLocation="none" ID="0" label="FSMs.vue"
    created="1498504287796" x="0.0" y="0.0" width="1.4E-45"
    height="1.4E-45" strokeWidth="0.0" autoSized="false">
    <resource referenceCreated="1498939858184" size="59106"
        spec="C:\Users\dries\Desktop\FSMs.vue" type="1" xsi:type="URLResource">
        <title>FSMs.vue</title>
        <property key="File" value="C:\Users\dries\Desktop\FSMs.vue"/>
    </resource>
    <fillColor>#FFFFFF</fillColor>
    <strokeColor>#404040</strokeColor>
    <textColor>#000000</textColor>
    <font>SansSerif-plain-14</font>
    <URIString>http://vue.tufts.edu/rdf/resource/e5e513d5c0a8020d00726a691ed5390d</URIString>
    <child ID="6" label="&#xa;Go to grid&#xa;" layerID="1"
        created="1498504298570" x="-227.00012" y="-132.83334"
        width="64.0" height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d5c0a8020d00726a696c5d6156</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="8"
        label="&#xa;Follow the &quot;Large Square&quot;&#xa;of the grid to reach all&#xa;four corners&#xa;"
        layerID="1" created="1498504350340" x="-272.00012"
        y="-31.333336" width="153.0" height="83.0" strokeWidth="1.0"
        autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d5c0a8020d00726a6988224a5d</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="9"
        label="&#xa;Follow a &quot;Small Square&quot;&#xa;of the grid to reach the&#xa;remaining two grid points&#xa;"
        layerID="1" created="1498504371569" x="-272.00012" y="101.66669"
        width="150.0" height="83.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a6951c0291d</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="10" label="Grid reached" layerID="1"
        created="1498504443858" x="-226.71794" y="-80.33203"
        width="63.0" height="49.5" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a6962448272</URIString>
        <point1 x="-195.11386" y="-79.83203"/>
        <point2 x="-195.32202" y="-31.332031"/>
        <ID1 xsi:type="node">6</ID1>
        <ID2 xsi:type="node">8</ID2>
    </child>
    <child ID="12" label="Four corners&#xa;reached" layerID="1"
        created="1498504477777" x="-227.75012" y="51.166016"
        width="63.0" height="51.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a6914dd4d30</URIString>
        <point1 x="-195.96815" y="51.666016"/>
        <point2 x="-196.53207" y="101.666016"/>
        <ID1 xsi:type="node">8</ID1>
        <ID2 xsi:type="node">9</ID2>
    </child>
    <child ID="13" label="&#xa;Move towards the&#xa;blue pillar&#xa;"
        layerID="1" created="1498504492666" x="-251.00012" y="243.66664"
        width="106.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a69a787eef4</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="14"
        label="&#xa;Play sound&#xa;&quot;Maze Found&quot;&#xa;"
        layerID="1" created="1498504522839" x="-243.00012" y="372.66663"
        width="85.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a6924de13ef</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="15" label="&#xa;Solve the maze&#xa;" layerID="1"
        created="1498504533184" x="-247.00012" y="497.66693"
        width="94.0" height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a69fcc201a3</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="16"
        label="&#xa;Play sound&#xa;&quot;Completed&quot;&#xa;"
        layerID="1" created="1498504538303" x="-239.00012" y="622.66693"
        width="80.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a69612382bb</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="17" label="Middle of grid&#xa;reached" layerID="1"
        created="1498504581717" x="-229.528" y="184.16602" width="64.0"
        height="60.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513d9c0a8020d00726a696ca55c50</URIString>
        <point1 x="-197.30867" y="184.66602"/>
        <point2 x="-197.74733" y="243.66602"/>
        <ID1 xsi:type="node">9</ID1>
        <ID2 xsi:type="node">13</ID2>
    </child>
    <child ID="18" label="Found&#xa;maze" layerID="1"
        created="1498504601192" x="-214.25012" y="311.167" width="30.0"
        height="62.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513ddc0a8020d00726a69a25cc321</URIString>
        <point1 x="-198.65903" y="311.667"/>
        <point2 x="-199.8412" y="372.667"/>
        <ID1 xsi:type="node">13</ID1>
        <ID2 xsi:type="node">14</ID2>
    </child>
    <child ID="19" label="Done playing&#xa;sound" layerID="1"
        created="1498504632982" x="-231.23416" y="440.16797"
        width="62.0" height="58.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513ddc0a8020d00726a69a281506b</URIString>
        <point1 x="-200.35545" y="440.66797"/>
        <point2 x="-200.11288" y="497.66797"/>
        <ID1 xsi:type="node">14</ID1>
        <ID2 xsi:type="node">15</ID2>
    </child>
    <child ID="20" label="Solved&#xa;maze" layerID="1"
        created="1498504648610" x="-216.02843" y="550.166" width="33.0"
        height="73.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513ddc0a8020d00726a69d3c574ee</URIString>
        <point1 x="-199.80013" y="550.666"/>
        <point2 x="-199.25673" y="622.666"/>
        <ID1 xsi:type="node">15</ID1>
        <ID2 xsi:type="node">16</ID2>
    </child>
    <child ID="39" layerID="1" created="1498505120518" x="-196.00186"
        y="-176.56772" width="1.3110809" height="44.233734"
        strokeWidth="1.0" autoSized="false" controlCount="0"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513eac0a8020d00726a691d957ea6</URIString>
        <point1 x="-195.50186" y="-176.06772"/>
        <point2 x="-195.19078" y="-132.83398"/>
        <ID2 xsi:type="node">6</ID2>
    </child>
    <child ID="42" label="&#xa;Turn Right&#xa;(slightly)&#xa;"
        layerID="1" created="1498922226161" x="-1046.6019" y="141.5327"
        width="68.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d001216897294b71d</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="43" label="&#xa;Drive Forward&#xa;" layerID="1"
        created="1498922228492" x="-801.0221" y="139.59453" width="87.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d00121689444a546a</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="44" label="&#xa;Turn Left&#xa;(slightly)&#xa;"
        layerID="1" created="1498922229894" x="-538.6286" y="134.6782"
        width="59.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d001216899f553914</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="45" label="OFF_PATH" layerID="1" created="1498922300369"
        x="-979.1019" y="185.14978" width="179.24933" height="23.756561"
        strokeWidth="1.0" autoSized="false" controlCount="1"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d0012168910adf250</URIString>
        <point1 x="-800.3526" y="185.91136"/>
        <point2 x="-978.6019" y="185.64978"/>
        <ID1 xsi:type="node">43</ID1>
        <ID2 xsi:type="node">42</ID2>
        <ctrlPoint0 x="-869.77594" y="218.03214" xsi:type="point"/>
    </child>
    <child ID="46" label="ON_EDGE_OF_PATH" layerID="1"
        created="1498922322311" x="-979.1019" y="137.86215"
        width="178.57983" height="27.488174" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d0012168927c99c6f</URIString>
        <point1 x="-978.6019" y="164.85033"/>
        <point2 x="-801.0221" y="152.61783"/>
        <ID1 xsi:type="node">42</ID1>
        <ID2 xsi:type="node">43</ID2>
        <ctrlPoint0 x="-870.83136" y="130.99022" xsi:type="point"/>
    </child>
    <child ID="47" label="TOO_MUCH_ON_PATH" layerID="1"
        created="1498922339037" x="-714.5221" y="179.49052"
        width="176.3935" height="23.717148" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d00121689bb9450dd</URIString>
        <point1 x="-714.0221" y="180.84035"/>
        <point2 x="-538.6286" y="179.99052"/>
        <ID1 xsi:type="node">43</ID1>
        <ID2 xsi:type="node">44</ID2>
        <ctrlPoint0 x="-622.1019" y="211.99991" xsi:type="point"/>
    </child>
    <child ID="48" label="ON_EDGE_OF_PATH" layerID="1"
        created="1498922425616" x="-714.5221" y="136.23889"
        width="176.3935" height="22.069809" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d00121689fb3030b8</URIString>
        <point1 x="-538.6286" y="157.8087"/>
        <point2 x="-714.0221" y="155.1469"/>
        <ID1 xsi:type="node">44</ID1>
        <ID2 xsi:type="node">43</ID2>
        <ctrlPoint0 x="-614.1019" y="129.99998" xsi:type="point"/>
    </child>
    <child ID="49" label="&#xa;Turn Right&#xa;(full turn)&#xa;"
        layerID="1" created="1498922489675" x="-1047.0018" y="302.19998"
        width="68.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d0012168905d285da</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="50" label="&#xa;Turn Left&#xa;(full turn&#xa;"
        layerID="1" created="1498922501227" x="-539.70197" y="293.4"
        width="59.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0686ec0a8020d00121689b15ce121</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="51" label="TURNING_LONGER_THAN_USUAL" layerID="1"
        created="1498922656160" x="-1096.3019" y="209.03125"
        width="167.0" height="93.65625" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d00121689ad57dad4</URIString>
        <point1 x="-1012.6865" y="209.53125"/>
        <point2 x="-1012.9172" y="302.1875"/>
        <ID1 xsi:type="node">42</ID1>
        <ID2 xsi:type="node">49</ID2>
    </child>
    <child ID="52" label="TURNING_LONGER_THAN_USUAL" layerID="1"
        created="1498922678251" x="-593.1653" y="202.17969"
        width="167.0" height="91.71875" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d001216890f218c69</URIString>
        <point1 x="-509.35855" y="202.67969"/>
        <point2 x="-509.97202" y="293.39844"/>
        <ID1 xsi:type="node">44</ID1>
        <ID2 xsi:type="node">50</ID2>
    </child>
    <child ID="53" label="ON_EDGE_OF_PATH" layerID="1"
        created="1498922690751" x="-979.50183" y="192.09448"
        width="202.75085" height="134.00162" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d00121689e742ff46</URIString>
        <point1 x="-979.00183" y="325.5961"/>
        <point2 x="-777.251" y="192.59448"/>
        <ID1 xsi:type="node">49</ID1>
        <ID2 xsi:type="node">43</ID2>
        <ctrlPoint0 x="-845.2019" y="283.86667" xsi:type="point"/>
    </child>
    <child ID="54" label="ON_EDGE_OF_PATH" layerID="1"
        created="1498922710290" x="-743.2911" y="192.09448"
        width="204.08911" height="132.12527" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d00121689e50e8d44</URIString>
        <point1 x="-539.70197" y="323.71976"/>
        <point2 x="-742.7911" y="192.59448"/>
        <ID1 xsi:type="node">50</ID1>
        <ID2 xsi:type="node">43</ID2>
        <ctrlPoint0 x="-679.60187" y="306.2667" xsi:type="point"/>
    </child>
    <child ID="55" label="&#xa;Find Path&#xa;" layerID="1"
        created="1498922991073" x="-789.1019" y="358.4" width="63.0"
        height="53.0" strokeWidth="1.0" strokeStyle="2" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d001216890aab7c20</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="56" label="PATH_FOUND" layerID="1"
        created="1498923004381" x="-791.562" y="192.125" width="68.0"
        height="166.75" strokeWidth="1.0" strokeStyle="2"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d0012168960c13bca</URIString>
        <point1 x="-757.5922" y="358.375"/>
        <point2 x="-757.5318" y="192.625"/>
        <ID1 xsi:type="node">55</ID1>
        <ID2 xsi:type="node">43</ID2>
    </child>
    <child ID="59" label="TURNING_TOO_LONG&#xa;(lost path)" layerID="1"
        created="1498923047203" x="-979.50183" y="342.18317"
        width="190.8999" height="37.21039" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="0"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06872c0a8020d001216896289fc76</URIString>
        <point1 x="-979.00183" y="342.68317"/>
        <point2 x="-789.1019" y="378.89355"/>
        <ID1 xsi:type="node">49</ID1>
        <ID2 xsi:type="node">55</ID2>
    </child>
    <child ID="60" label="TURNING_TOO_LONG&#xa;(lost path)" layerID="1"
        created="1498923055670" x="-726.6019" y="333.7563"
        width="187.39996" height="44.32257" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="0"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d001216894378fe21</URIString>
        <point1 x="-539.70197" y="334.2563"/>
        <point2 x="-726.1019" y="377.57886"/>
        <ID1 xsi:type="node">50</ID1>
        <ID2 xsi:type="node">55</ID2>
    </child>
    <child ID="61" layerID="1" created="1498923122621" x="-758.50195"
        y="76.16667" width="1.3375854" height="63.92708"
        strokeWidth="1.0" autoSized="false" controlCount="0"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d0012168906e1aca0</URIString>
        <point1 x="-758.0019" y="76.66667"/>
        <point2 x="-757.6643" y="139.59375"/>
        <ID2 xsi:type="node">43</ID2>
    </child>
    <child ID="63" label="&#xa;Follow the path&#xa;" layerID="1"
        created="1498923438511" x="183.06467" y="186.99998" width="94.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d001216895b0432ea</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="64" label="&#xa;Slow down&#xa;" layerID="1"
        created="1498923466652" x="391.06464" y="255.99986" width="71.0"
        height="53.0" strokeWidth="1.0" strokeStyle="2" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d00121689f0aaa76d</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="65" label="&#xa;Speed up&#xa;" layerID="1"
        created="1498923472331" x="-28.935333" y="254.99986"
        width="64.0" height="53.0" strokeWidth="1.0" strokeStyle="2"
        autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d0012168913bb174b</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="66" label="Going up a slope" layerID="1"
        created="1498923497461" x="32.8195" y="212.82195"
        width="150.74518" height="47.362625" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="1"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d0012168936971b29</URIString>
        <point1 x="183.06467" y="213.32195"/>
        <point2 x="33.3195" y="259.68457"/>
        <ID1 xsi:type="node">63</ID1>
        <ID2 xsi:type="node">65</ID2>
        <ctrlPoint0 x="98.06467" y="212.99995" xsi:type="point"/>
    </child>
    <child ID="67" label="Back in vertical&#xa;position" layerID="1"
        created="1498923517901" x="34.564667" y="239.49998"
        width="164.31842" height="57.808304" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="1"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d00121689c7bbdf0f</URIString>
        <point1 x="35.064667" y="287.23322"/>
        <point2 x="198.38309" y="239.99998"/>
        <ID1 xsi:type="node">65</ID1>
        <ID2 xsi:type="node">63</ID2>
        <ctrlPoint0 x="123.06467" y="302.99994" xsi:type="point"/>
    </child>
    <child ID="68" label="Going down a slope" layerID="1"
        created="1498923531192" x="276.56467" y="213.98737"
        width="120.78534" height="43.515503" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="1"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d0012168945280468</URIString>
        <point1 x="277.06467" y="214.48737"/>
        <point2 x="396.85" y="257.00287"/>
        <ID1 xsi:type="node">63</ID1>
        <ID2 xsi:type="node">64</ID2>
        <ctrlPoint0 x="349.06464" y="215.99995" xsi:type="point"/>
    </child>
    <child ID="69" label="Back in vertical&#xa;position" layerID="1"
        created="1498923540532" x="261.49637" y="239.49998"
        width="130.06827" height="53.15071" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="1"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d00121689b3911de8</URIString>
        <point1 x="391.06464" y="286.6029"/>
        <point2 x="261.99637" y="239.99998"/>
        <ID1 xsi:type="node">64</ID1>
        <ID2 xsi:type="node">63</ID2>
        <ctrlPoint0 x="327.06464" y="293.99994" xsi:type="point"/>
    </child>
    <child ID="70" layerID="1" created="1498923634990" x="228.56464"
        y="150.5" width="1.5760193" height="36.999985" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06876c0a8020d001216893e110be5</URIString>
        <point1 x="229.06464" y="151.00002"/>
        <point2 x="229.64066" y="187.0"/>
        <ID2 xsi:type="node">63</ID2>
    </child>
    <child ID="73" label="&#xa;Look for&#xa;a pillar&#xa;" layerID="1"
        created="1498923798762" x="779.5648" y="104.33335" width="55.0"
        height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d0012168975b6f744</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="74" label="&#xa;Move towards&#xa;pillar&#xa;" layerID="1"
        created="1498923915133" x="763.5647" y="239.33333" width="86.0"
        height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d001216895e9ccb11</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="75" label="&#xa;Distinguish&#xa;pillar color&#xa;"
        layerID="1" created="1498923920654" x="766.5647" y="384.33325"
        width="74.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d00121689895ee051</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="76" label="&#xa;Kill pillar&#xa;" layerID="1"
        created="1498923929962" x="637.5647" y="551.3336" width="58.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d0012168916d44a00</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="77" label="&#xa;Court pillar&#xa;" layerID="1"
        created="1498923935892" x="901.5647" y="551.3336" width="71.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d00121689a63b8262</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="78" label="&#xa;Turn around&#xa;" layerID="1"
        created="1498923976201" x="559.56476" y="-26.333336"
        width="78.0" height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d00121689b03222a0</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="79" label="Hit the edge&#xa;of the environment"
        layerID="1" created="1498924238961" x="637.06476" y="5.689995"
        width="153.2044" height="99.14338" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d0012168934a6ffd4</URIString>
        <point1 x="789.76917" y="104.333374"/>
        <point2 x="637.56476" y="6.189995"/>
        <ID1 xsi:type="node">73</ID1>
        <ID2 xsi:type="node">78</ID2>
        <ctrlPoint0 x="748.5648" y="23.33332" xsi:type="point"/>
    </child>
    <child ID="80" label="Pillar found" layerID="1"
        created="1498924253573" x="780.3148" y="171.82812" width="53.0"
        height="68.015625" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d001216897d48c47f</URIString>
        <point1 x="806.9389" y="172.32812"/>
        <point2 x="806.6907" y="239.34375"/>
        <ID1 xsi:type="node">73</ID1>
        <ID2 xsi:type="node">74</ID2>
    </child>
    <child ID="81" label="In front of&#xa;pillar" layerID="1"
        created="1498924261644" x="781.5647" y="306.83203" width="47.0"
        height="78.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ac0a8020d0012168954160ae1</URIString>
        <point1 x="805.86127" y="307.33203"/>
        <point2 x="804.2681" y="384.33203"/>
        <ID1 xsi:type="node">74</ID1>
        <ID2 xsi:type="node">75</ID2>
    </child>
    <child ID="82" label="Pillar is red" layerID="1"
        created="1498924283851" x="688.27057" y="451.45404"
        width="86.91614" height="101.02673" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d00121689803655d8</URIString>
        <point1 x="774.6867" y="451.95404"/>
        <point2 x="688.77057" y="551.9808"/>
        <ID1 xsi:type="node">75</ID1>
        <ID2 xsi:type="node">76</ID2>
    </child>
    <child ID="83" label="Pillar is blue" layerID="1"
        created="1498924288941" x="831.3116" y="451.58148"
        width="84.072876" height="100.252075" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d00121689ef8e8055</URIString>
        <point1 x="831.8116" y="452.08148"/>
        <point2 x="914.88446" y="551.33356"/>
        <ID1 xsi:type="node">75</ID1>
        <ID2 xsi:type="node">77</ID2>
    </child>
    <child ID="84" label="&#xa;Move forward&#xa;a little&#xa;"
        layerID="1" created="1498924311783" x="952.2314" y="-36.0"
        width="83.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d001216899fe540c3</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="85" label="Cannot find pillar" layerID="1"
        created="1498924352463" x="820.3788" y="3.853836"
        width="132.3526" height="100.97954" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d001216896e60470c</URIString>
        <point1 x="820.8788" y="104.333374"/>
        <point2 x="952.2314" y="4.353836"/>
        <ID1 xsi:type="node">73</ID1>
        <ID2 xsi:type="node">84</ID2>
        <ctrlPoint0 x="855.48145" y="19.166666" xsi:type="point"/>
    </child>
    <child ID="86" label="Done&#xa;turning" layerID="1"
        created="1498924369671" x="616.1942" y="26.166687"
        width="163.8706" height="106.53284" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d00121689dcbd7e7a</URIString>
        <point1 x="616.6942" y="26.666687"/>
        <point2 x="779.5648" y="132.19952"/>
        <ID1 xsi:type="node">78</ID1>
        <ID2 xsi:type="node">73</ID2>
        <ctrlPoint0 x="672.5648" y="108.33335" xsi:type="point"/>
    </child>
    <child ID="87" label="Done&#xa;moving" layerID="1"
        created="1498924373313" x="834.0648" y="31.5" width="139.00977"
        height="99.57399" strokeWidth="1.0" autoSized="false"
        controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d001216890396ae6e</URIString>
        <point1 x="972.5746" y="32.0"/>
        <point2 x="834.5648" y="130.57399"/>
        <ID1 xsi:type="node">84</ID1>
        <ID2 xsi:type="node">73</ID2>
        <ctrlPoint0 x="927.5647" y="104.33335" xsi:type="point"/>
    </child>
    <child ID="88" label="Pillar&#xa;killed" layerID="1"
        created="1498924549330" x="648.3316" y="163.06378"
        width="131.98163" height="388.7697" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d0012168940e7b698</URIString>
        <point1 x="660.6441" y="551.3335"/>
        <point2 x="779.81323" y="163.56378"/>
        <ID1 xsi:type="node">76</ID1>
        <ID2 xsi:type="node">73</ID2>
        <ctrlPoint0 x="609.28265" y="321.44684" xsi:type="point"/>
    </child>
    <child ID="89" label="Courtship&#xa;completed" layerID="1"
        created="1498924562887" x="833.6259" y="164.00702"
        width="135.05817" height="387.82648" strokeWidth="1.0"
        autoSized="false" controlCount="1" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d001216898838c2df</URIString>
        <point1 x="943.59564" y="551.3335"/>
        <point2 x="834.1259" y="164.50702"/>
        <ID1 xsi:type="node">77</ID1>
        <ID2 xsi:type="node">73</ID2>
        <ctrlPoint0 x="999.5073" y="324.46503" xsi:type="point"/>
    </child>
    <child ID="90" label="&#xa;Cross bridge&#xa;" layerID="1"
        created="1498924814062" x="1511.4813" y="-80.566666"
        width="83.0" height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d00121689a01f7f22</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="92" label="&#xa;Follow path&#xa;" layerID="1"
        created="1498924840214" x="1387.4813" y="28.500023" width="74.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef0687ec0a8020d001216895ffccb48</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="93" label="&#xa;Check pillar&#xa;" layerID="1"
        created="1498924912666" x="1387.4816" y="132.50002" width="76.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d001216894fea8929</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="94" label="&#xa;Continue&#xa;along path&#xa;" layerID="1"
        created="1498924920456" x="1390.1481" y="241.83334" width="69.0"
        height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d0012168997e0b6c5</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="95" label="&#xa;Carefully move&#xa;to food&#xa;"
        layerID="1" created="1498924934452" x="1380.8146" y="365.83337"
        width="92.0" height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d0012168978075da3</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="96" label="&#xa;Pick up food&#xa;" layerID="1"
        created="1498924946026" x="1387.4814" y="491.16663" width="78.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d00121689e0d9035c</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="97" label="&#xa;Turn around&#xa;" layerID="1"
        created="1498924949904" x="1514.9484" y="599.7" width="78.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d00121689fce5afef</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="98" label="&#xa;Return to&#xa;bridge&#xa;" layerID="1"
        created="1498924962244" x="1654.1481" y="493.83337" width="61.0"
        height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d001216892d9f998e</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="99" label="&#xa;Cross bridge&#xa;" layerID="1"
        created="1498924969524" x="1647.4813" y="383.1667" width="83.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d0012168942a72d2d</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="100" label="&#xa;Move to 'home'&#xa;" layerID="1"
        created="1498924977003" x="1644.815" y="256.50006" width="91.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d0012168979dab963</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="101" label="&#xa;Drop food&#xa;" layerID="1"
        created="1498924988056" x="1660.8147" y="133.83327" width="65.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d0012168933394bdd</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="102" label="&#xa;Turn around&#xa;" layerID="1"
        created="1498925044124" x="1195.4814" y="75.16669" width="78.0"
        height="53.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d00121689f0b07c6d</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="104" label="&#xa;Return to&#xa;bridge&#xa;" layerID="1"
        created="1498925081215" x="1660.8148" y="13.833374" width="61.0"
        height="68.0" strokeWidth="1.0" autoSized="true" xsi:type="node">
        <fillColor>#FFFFFF</fillColor>
        <strokeColor>#000000</strokeColor>
        <textColor>#000000</textColor>
        <font>Arial-plain-12</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d001216891c91dd40</URIString>
        <shape arcwidth="20.0" archeight="20.0" xsi:type="roundRect"/>
    </child>
    <child ID="105" label="Crossroads&#xa;reached" layerID="1"
        created="1498925346482" x="1454.3918" y="-28.06665"
        width="67.8678" height="57.75525" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d00121689b058591d</URIString>
        <point1 x="1521.7596" y="-27.56665"/>
        <point2 x="1454.8918" y="29.188599"/>
        <ID1 xsi:type="node">90</ID1>
        <ID2 xsi:type="node">92</ID2>
    </child>
    <child ID="106" label="Close to&#xa;pillar" layerID="1"
        created="1498925388223" x="1405.4814" y="81.0" width="39.0"
        height="52.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d00121689e4db1597</URIString>
        <point1 x="1424.7362" y="81.5"/>
        <point2 x="1425.2267" y="132.5"/>
        <ID1 xsi:type="node">92</ID1>
        <ID2 xsi:type="node">93</ID2>
    </child>
    <child ID="107" label="Pillar is blue" layerID="1"
        created="1498925400442" x="1397.0916" y="185.0" width="56.0"
        height="57.328125" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06882c0a8020d001216897dfbb437</URIString>
        <point1 x="1425.2925" y="185.5"/>
        <point2 x="1424.8906" y="241.82812"/>
        <ID1 xsi:type="node">93</ID1>
        <ID2 xsi:type="node">94</ID2>
    </child>
    <child ID="108" label="Pillar is red" layerID="1"
        created="1498925404992" x="1272.9814" y="112.873474"
        width="115.00012" height="35.21994" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689345b24bf</URIString>
        <point1 x="1387.4816" y="147.59341"/>
        <point2 x="1273.4814" y="113.373474"/>
        <ID1 xsi:type="node">93</ID1>
        <ID2 xsi:type="node">102</ID2>
    </child>
    <child ID="109" label="Done turning" layerID="1"
        created="1498925414213" x="1272.9814" y="63.587738"
        width="114.99988" height="29.0" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689c2ec9cc2</URIString>
        <point1 x="1273.4814" y="92.08774"/>
        <point2 x="1387.4813" y="64.08774"/>
        <ID1 xsi:type="node">102</ID1>
        <ID2 xsi:type="node">92</ID2>
    </child>
    <child ID="110" label="Close enough&#xa;to food" layerID="1"
        created="1498925425401" x="1392.7313" y="309.33594" width="66.0"
        height="57.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689d4069341</URIString>
        <point1 x="1425.2421" y="309.83594"/>
        <point2 x="1426.2206" y="365.83594"/>
        <ID1 xsi:type="node">94</ID1>
        <ID2 xsi:type="node">95</ID2>
    </child>
    <child ID="111" label="Food between&#xa;arms" layerID="1"
        created="1498925446372" x="1391.6375" y="433.3125" width="70.0"
        height="58.34375" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d0012168963a6226c</URIString>
        <point1 x="1426.7185" y="433.8125"/>
        <point2 x="1426.5564" y="491.15625"/>
        <ID1 xsi:type="node">95</ID1>
        <ID2 xsi:type="node">96</ID2>
    </child>
    <child ID="112" label="Picked up&#xa;food" layerID="1"
        created="1498925455431" x="1456.6973" y="543.32007"
        width="67.03516" height="57.22644" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d001216891c44ecc6</URIString>
        <point1 x="1457.1973" y="543.82007"/>
        <point2 x="1523.2324" y="600.0465"/>
        <ID1 xsi:type="node">96</ID1>
        <ID2 xsi:type="node">97</ID2>
    </child>
    <child ID="113" label="Done&#xa;turning" layerID="1"
        created="1498925464113" x="1587.013" y="550.2882"
        width="67.63513" height="51.150635" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689c9e1a894</URIString>
        <point1 x="1587.513" y="600.93884"/>
        <point2 x="1654.1481" y="550.7882"/>
        <ID1 xsi:type="node">97</ID1>
        <ID2 xsi:type="node">98</ID2>
    </child>
    <child ID="114" label="Crossroads&#xa;reached" layerID="1"
        created="1498925479491" x="1658.4521" y="435.66797" width="57.0"
        height="58.664062" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689b7b6196b</URIString>
        <point1 x="1685.8949" y="493.83203"/>
        <point2 x="1688.0095" y="436.16797"/>
        <ID1 xsi:type="node">98</ID1>
        <ID2 xsi:type="node">99</ID2>
    </child>
    <child ID="115" label="Detected&#xa;pillar" layerID="1"
        created="1498925485832" x="1668.1482" y="309.0" width="43.0"
        height="74.671875" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689f7486598</URIString>
        <point1 x="1689.2603" y="383.17188"/>
        <point2 x="1690.036" y="309.5"/>
        <ID1 xsi:type="node">99</ID1>
        <ID2 xsi:type="node">100</ID2>
    </child>
    <child ID="116" label="Close enough&#xa;to pillar" layerID="1"
        created="1498925510494" x="1658.8148" y="186.33594" width="66.0"
        height="70.66406" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d001216899c7b0759</URIString>
        <point1 x="1690.963" y="256.5"/>
        <point2 x="1692.6666" y="186.83594"/>
        <ID1 xsi:type="node">100</ID1>
        <ID2 xsi:type="node">101</ID2>
    </child>
    <child ID="117" label="Food&#xa;dropped" layerID="1"
        created="1498925524614" x="1672.3813" y="81.33594" width="40.0"
        height="53.0" strokeWidth="1.0" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689a1cff570</URIString>
        <point1 x="1692.8435" y="133.83594"/>
        <point2 x="1691.9192" y="81.83594"/>
        <ID1 xsi:type="node">101</ID1>
        <ID2 xsi:type="node">104</ID2>
    </child>
    <child ID="118" label="In front&#xa;of bridge" layerID="1"
        created="1498925530455" x="1587.4935" y="-28.775879"
        width="73.82129" height="54.64209" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689fa4a70ac</URIString>
        <point1 x="1660.8148" y="25.36621"/>
        <point2 x="1587.9935" y="-28.275879"/>
        <ID1 xsi:type="node">104</ID1>
        <ID2 xsi:type="node">90</ID2>
    </child>
    <child ID="119" layerID="1" created="1498925679423" x="805.31464"
        y="-51.3" width="2.0253906" height="156.13594" strokeWidth="1.0"
        autoSized="false" controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689a7e4526b</URIString>
        <point1 x="805.81464" y="-50.8"/>
        <point2 x="806.84" y="104.33594"/>
        <ID2 xsi:type="node">73</ID2>
    </child>
    <child ID="121" layerID="1" created="1498925702414" x="1551.9983"
        y="-130.96771" width="1.3155518" height="50.905212"
        strokeWidth="1.0" autoSized="false" controlCount="0"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/fef06886c0a8020d00121689542ccd9e</URIString>
        <point1 x="1552.4982" y="-130.46771"/>
        <point2 x="1552.8137" y="-80.5625"/>
        <ID2 xsi:type="node">90</ID2>
    </child>
    <child ID="122" layerID="1" created="1498939733878" x="-916.8019"
        y="-133.56772" width="60.0" height="1.5" strokeWidth="1.0"
        strokeStyle="2" autoSized="false" controlCount="0"
        arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ffc71d37c0a8020d008a840790ba4db3</URIString>
        <point1 x="-916.3019" y="-133.06772"/>
        <point2 x="-857.3019" y="-132.56772"/>
    </child>
    <child ID="123" label="Not actually implemented in ScorpI/O"
        layerID="1" created="1498939743292" x="-847.3019" y="-138.56772"
        width="222.0" height="31.0" strokeWidth="0.0" autoSized="false" xsi:type="text">
        <strokeColor>#404040</strokeColor>
        <textColor>#000000</textColor>
        <font>SansSerif-plain-14</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ffc71d37c0a8020d008a84074dd2e584</URIString>
        <richText>&lt;html&gt;
  &lt;head style="color: #404040" color="#404040"&gt;
    &lt;style type="text/css"&gt;
      &lt;!--
        body { font-size: 11; color: #404040; margin-right: 0px; margin-left: 0px; margin-bottom: 0px; margin-top: 0px; font-family: Arial }
        ol { font-size: 11; margin-left: 30; vertical-align: middle; list-style-position: outside; margin-top: 6; font-family: Arial }
        p { color: #404040; margin-right: 0; margin-left: 0; margin-bottom: 0; margin-top: 0 }
        ul { font-size: 11; margin-left: 30; vertical-align: middle; list-style-position: outside; margin-top: 6; font-family: Arial }
      --&gt;
    &lt;/style&gt;
    
  &lt;/head&gt;
  &lt;body&gt;
    &lt;p style="color: #404040" color="#404040"&gt;
      Not actually implemented in ScorpI/O
    &lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
</richText>
        <label>Not actually implemented in ScorpI/O</label>
    </child>
    <child ID="125" label="MISSCHIEN GESTIPPELD?" layerID="1"
        created="1498939792041" x="1226.1146" y="-55.317707"
        width="149.0" height="20.0" strokeWidth="0.0" autoSized="false" xsi:type="text">
        <strokeColor>#404040</strokeColor>
        <textColor>#000000</textColor>
        <font>SansSerif-plain-14</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ffc71d47c0a8020d008a840766c4a9c7</URIString>
        <richText>&lt;html&gt;
  &lt;head style="color: #404040" color="#404040"&gt;
    &lt;style type="text/css"&gt;
      &lt;!--
        body { font-size: 11; color: #404040; margin-right: 0px; margin-left: 0px; margin-bottom: 0px; margin-top: 0px; font-family: Arial }
        ol { font-size: 11; margin-left: 30; vertical-align: middle; list-style-position: outside; margin-top: 6; font-family: Arial }
        p { color: #404040; margin-right: 0; margin-left: 0; margin-bottom: 0; margin-top: 0 }
        ul { font-size: 11; margin-left: 30; vertical-align: middle; list-style-position: outside; margin-top: 6; font-family: Arial }
      --&gt;
    &lt;/style&gt;
    
  &lt;/head&gt;
  &lt;body&gt;
    &lt;p style="color: #404040" color="#404040"&gt;
      MISSCHIEN GESTIPPELD?
    &lt;/p&gt;
  &lt;/body&gt;
&lt;/html&gt;
</richText>
        <label>MISSCHIEN GESTIPPELD?</label>
    </child>
    <child ID="126" layerID="1" created="1498939805825" x="1244.2812"
        y="-35.817627" width="51.75757" height="100.999916"
        strokeWidth="1.0" strokeStyle="2" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ffc71d48c0a8020d008a84077fffba8e</URIString>
        <point1 x="1295.5388" y="-35.317627"/>
        <point2 x="1244.7812" y="64.68229"/>
        <ID1 xsi:type="text">125</ID1>
    </child>
    <child ID="127" layerID="1" created="1498939810114" x="1305.4941"
        y="-35.817627" width="87.78723" height="162.33325"
        strokeWidth="1.0" strokeStyle="2" autoSized="false"
        controlCount="0" arrowState="2" xsi:type="link">
        <strokeColor>#404040</strokeColor>
        <textColor>#404040</textColor>
        <font>Arial-plain-11</font>
        <URIString>http://vue.tufts.edu/rdf/resource/ffc71d48c0a8020d008a8407cf5a79bb</URIString>
        <point1 x="1305.994" y="-35.317627"/>
        <point2 x="1392.7812" y="126.015625"/>
        <ID1 xsi:type="text">125</ID1>
    </child>
    <layer ID="1" label="Layer 1" created="1498504287799" x="0.0"
        y="0.0" width="1.4E-45" height="1.4E-45" strokeWidth="0.0" autoSized="false">
        <URIString>http://vue.tufts.edu/rdf/resource/e5e513ecc0a8020d00726a69d9bc2d1a</URIString>
    </layer>
    <userZoom>0.75</userZoom>
    <userOrigin x="-1259.4141" y="-178.48828"/>
    <presentationBackground>#202020</presentationBackground>
    <PathwayList currentPathway="0" revealerIndex="-1">
        <pathway ID="0" label="Untitled Pathway" created="1498504287795"
            x="0.0" y="0.0" width="1.4E-45" height="1.4E-45"
            strokeWidth="0.0" autoSized="false" currentIndex="0" open="true">
            <strokeColor>#B3993333</strokeColor>
            <textColor>#000000</textColor>
            <font>SansSerif-plain-14</font>
            <URIString>http://vue.tufts.edu/rdf/resource/e5e513ecc0a8020d00726a692c9ec60f</URIString>
            <masterSlide ID="2" created="1498504287817" x="0.0" y="0.0"
                width="800.0" height="600.0" locked="true"
                strokeWidth="0.0" autoSized="false">
                <fillColor>#000000</fillColor>
                <strokeColor>#404040</strokeColor>
                <textColor>#000000</textColor>
                <font>SansSerif-plain-14</font>
                <URIString>http://vue.tufts.edu/rdf/resource/e5e513edc0a8020d00726a69d038ea4c</URIString>
                <titleStyle ID="3" label="Header"
                    created="1498504288160" x="335.5" y="172.5"
                    width="129.0" height="55.0" strokeWidth="0.0"
                    autoSized="true" isStyle="true" xsi:type="node">
                    <strokeColor>#404040</strokeColor>
                    <textColor>#FFFFFF</textColor>
                    <font>Gill Sans-plain-36</font>
                    <URIString>http://vue.tufts.edu/rdf/resource/e5e513edc0a8020d00726a69f7d14c96</URIString>
                    <shape xsi:type="rectangle"/>
                </titleStyle>
                <textStyle ID="4" label="Slide Text"
                    created="1498504288160" x="346.5" y="281.5"
                    width="107.0" height="37.0" strokeWidth="0.0"
                    autoSized="true" isStyle="true" xsi:type="node">
                    <strokeColor>#404040</strokeColor>
                    <textColor>#FFFFFF</textColor>
                    <font>Gill Sans-plain-22</font>
                    <URIString>http://vue.tufts.edu/rdf/resource/e5e513edc0a8020d00726a69801caa01</URIString>
                    <shape xsi:type="rectangle"/>
                </textStyle>
                <linkStyle ID="5" label="Links" created="1498504288160"
                    x="373.5" y="384.0" width="53.0" height="32.0"
                    strokeWidth="0.0" autoSized="true" isStyle="true" xsi:type="node">
                    <strokeColor>#404040</strokeColor>
                    <textColor>#B3BFE3</textColor>
                    <font>Gill Sans-plain-18</font>
                    <URIString>http://vue.tufts.edu/rdf/resource/e5e513edc0a8020d00726a69fef6c695</URIString>
                    <shape xsi:type="rectangle"/>
                </linkStyle>
            </masterSlide>
        </pathway>
    </PathwayList>
    <date>2017-06-26</date>
    <modelVersion>6</modelVersion>
    <saveLocation>C:\Users\dries\Desktop</saveLocation>
    <saveFile>C:\Users\dries\Desktop\FSMs.vue</saveFile>
</LW-MAP>
