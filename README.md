# jQuery plugin of tabs
___

# API
> # $.fn.initJerichoTab(Function):
> * renderTo(String): the tab render to('#sample')
> * uniqueId(String): the tab's id(It must be unique)
> * tabs(Array): the tabs will be initialized, whose items will be formated as follows:
>  	{
>  	**title(String): the tab title text
>  	**iconImg(String): the tab icon that displayed from title text,
>  	**closeable(Boolean): the switch that controls whether the tab can be closed (true as default)
>  	}
> * activeTabIndex(Int): the tab you'd like to select after loading(0 as default)
> * contentHeight(Int): height of the content div tag
> * contentCss(Object): the same as style sheet
> * loadOnce(Boolean): the switch controls if load tab content at the first time(true as default)
> * tabWidth(Int): width of each tab(150 as default)
>   
> * ***add by jeffen@pactera 2.16/1/17
> * isCookieTabsetting(Boolean): keep tabs setting status by cookie attribute(false as default)
> * isCookieLoadData(Boolean): auto load data by cookie keeping tabs(false as default)
> * cookieTabsetting(String): set cookie name for tabsetting(value limit by browser, eg. 2096)
> * fn_beforeAddTab(function): call the event before addTab
> * fn_afterTabMouseup(function): call the event after tab mouseup
> * fn_afterTabLoad(function): call the event after tab load data
> * openWithNewWidowAfterDblClick(Boolean): open a new window after tab double click tab
> * fn_tabDblClick(function): call the event after tab double click


# release log:
> * version: release-2.0.1 (05/13/2009) 
>* version: release-2.0.2 (01/17/2016) by jeffen@pactera
> * version: release-2.0.3 (06/02/2016) by jeffen@pactera