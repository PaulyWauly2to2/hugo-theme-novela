+++
authors = ["Paul Graham"]
date = 2022-05-05T23:00:00Z
excerpt = ""
hero = ""
title = "SharePoint Modern Page Tiles"

+++
    { 
    
    "$schema": "https://developer.microsoft.com/json-schemas/sp/v2/tile-formatting.schema.json", 
    
    "hideSelection": true, 
    
    "width": "202", 
    
    "height": "194", 
    
    "formatter": { 
    
    "elmType": "a", 
    
    "attributes": { 
    
    "href": "[$URL]", 
    
    "target": "'_blank')" 
    
    }, 
    
    "style": { 
    
    "text-decoration": "none" 
    
    }, 
    
    "children": [ 
    
    { 
    
    "elmType": "div", 
    
    "attributes": { 
    
    "class": "ms-bgColor-neutralLight ms-bgColor-neutralLighter--hover ms-fontColor-neutralDark ms-fontColor-neutralDark--hover" 
    
    }, 
    
    "style": { 
    
    "display": "flex", 
    
    "flex-wrap": "wrap", 
    
    "min-width": "200px", 
    
    "min-height": "180px", 
    
    "margin-right": "10px", 
    
    "margin-top": "10px", 
    
    "box-shadow": "2px 2px 4px darkgrey" 
    
    }, 
    
    "children": [ 
    
    { 
    
    "elmType": "div", 
    
    "style": { 
    
    "text-align": "center", 
    
    "margin": "auto" 
    
    }, 
    
    "children": [ 
    
    { 
    
    "elmType": "div", 
    
    "attributes": { 
    
    "class": "sp-row-title" 
    
    }, 
    
    "style": { 
    
    "font-weight": "400", 
    
    "font-size": "1.2em", 
    
    "padding-bottom": "0.6em" 
    
    }, 
    
    "txtContent": "[$Title]" 
    
    }, 
    
    { 
    
    "elmType": "img", 
    
    "style": { 
    
    "width": "50%" 
    
    }, 
    
    "attributes": { 
    
    "src": "[$ImageUrl]" 
    
    } 
    
    } 
    
    ] 
    
    } 
    
    ] 
    
    } 
    
    ] 
    
    } 
    
    } 