Bootstrap4AdminTable
===========
2019-08-15 -> 2021-03-05



An admin table renderer for bootstrap4.


This is part of the [universe framework](https://github.com/karayabin/universe-snapshot).


Install
==========
Using the [planet installer](https://github.com/lingtalfi/Light_PlanetInstaller) via [light-cli](https://github.com/lingtalfi/Light_Cli)
```bash
lt install Ling.Bootstrap4AdminTable
```

Using the [uni](https://github.com/lingtalfi/universe-naive-importer) command.
```bash
uni import Ling/Bootstrap4AdminTable
```

Or just download it and place it where you want otherwise.






Summary
===========
- [Bootstrap4AdminTable api](https://github.com/lingtalfi/Bootstrap4AdminTable/blob/master/doc/api/Ling/Bootstrap4AdminTable.md) (generated with [DocTools](https://github.com/lingtalfi/DocTools))
- [Notes](#notes)
- [Related](#related)



Notes
=========

This renderer was first created as a stand alone object.
But with the addition of the ajax layer, it turns out that it now depends on the [Light_Realist](https://github.com/lingtalfi/Light_Realist) plugin.

So, I'll not change the name, but you can consider this object as part of the [light framework](https://github.com/lingtalfi/Light) (i.e. it makes use of the service container
when necessary and is aware of the common services such as the html_page_copilot).






Related
==========
- [GuiAdminTable](https://github.com/lingtalfi/GuiAdminTable/), an older version
- [AdminTable](https://github.com/lingtalfi/AdminTable), an even older version




History Log
=============

- 1.15.8 -- 2021-05-31

    - Removing trailing plus in lpi-deps file (to work with Light_PlanetInstaller:2.0.0 api

- 1.15.7 -- 2021-03-05

    - update README.md, add install alternative

- 1.15.6 -- 2021-02-23

    - checkpoint commit for dependency update
  
- 1.15.5 -- 2021-02-22

    - adapt to new light universe assets organization
  
- 1.15.4 -- 2020-12-08

    - Fix lpi-deps not using natsort

- 1.15.3 -- 2020-12-04

    - Add lpi-deps.byml file

- 1.15.2 -- 2020-11-24

    - update Bootstrap4AdminTableRenderer->render, now cleans the master checkbox after any realist request  
    
- 1.15.1 -- 2020-11-24

    - update ToolbarRendererWidget, now renders more compact buttons    
    
- 1.15.0 -- 2020-09-03

    - update to adapt realist2 api   
    
- 1.14.1 -- 2020-07-06

    - fix functional typo   
    
- 1.14.0 -- 2020-07-06

    - update to accommodate new Light_Realist action -> _action evolution   
    
- 1.13.1 -- 2020-03-09

    - fix ToolbarRendererWidget rendering buttons with actionId=null   
    
- 1.13.0 -- 2020-03-05

    - update Bootstrap4AdminTableRenderer, add jsVars property   
    
- 1.12.2 -- 2019-11-18

    - fix Bootstrap4AdminTableRenderer functional typo with ajax handler url  
    
- 1.12.1 -- 2019-11-15

    - fix Bootstrap4AdminTableRenderer using hardcoded value for ajax handler service url 
    
- 1.12.0 -- 2019-11-12

    - update AdvancedSearchRendererWidget to accommodate new fields structure  
    
- 1.11.0 -- 2019-11-12

    - update Bootstrap4AdminTableRenderer to accommodate the new hiddenColumns concept  
    
- 1.10.0 -- 2019-11-11

    - update AdvancedSearchRendererWidget, now the fields property is an array of alias => colExpr  
    
- 1.9.1 -- 2019-11-07

    - clean Bootstrap4AdminTableRenderer, removed example rows
    
- 1.9.0 -- 2019-10-28

    - add RelatedLinksRendererWidget
    
- 1.8.0 -- 2019-10-11

    - adapt to new realist conception
    - fix AdvancedSearchRendererWidget using hardcoded values
    
- 1.7.3 -- 2019-10-07

    - fix ToolbarRendererWidget->return not handling nested toolbar items properly
    
- 1.7.2 -- 2019-10-04

    - fix problem returning duplicate rics

- 1.7.1 -- 2019-09-26

    - fix problem with un-synchronized DocBuilder not generating doc
    
- 1.7.0 -- 2019-09-25

    - implementation of list general actions
    
- 1.6.0 -- 2019-09-23

    - update ToolbarRendererWidget, now is csrf token aware and implements params with hep
    - update Bootstrap4AdminTableRenderer, fix the paths to external js standalone libs  
    
- 1.5.0 -- 2019-09-18

    - implementation of csrf token part
    
- 1.4.1 -- 2019-09-18

    - update ToolbarRendererWidgetInterface->setGroups, now accepts attr property
    
- 1.4.0 -- 2019-09-06

    - removed RendererWidgetInterface->prepare
    
- 1.3.0 -- 2019-09-06

    - renamed ActionButtonsRendererWidget to ToolbarRendererWidget

- 1.2.0 -- 2019-09-05

    - add master checkbox behaviour to Bootstrap4AdminTableRenderer
    
- 1.1.0 -- 2019-09-05

    - add NumberOfItemsPerPageRendererWidget
    
- 1.0.0 -- 2019-08-15

    - initial commit