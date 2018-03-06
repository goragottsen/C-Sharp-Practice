# C-Sharp-Practice
1) Create a masterpage and 3 Content pages (Home, GridView, GridDetail)
2) Add a Sitemap
3) Add the link nesting structure to the sitemap file _(see Web.sitemap)_
4) Create a menu in the masterfile at the top of the form: a) Insert a sitemap data source (Toolbox -> Data); b) Insert a sitemap data source (Toolbox -> Navigation)
5) Link the menu control to the **sitemapdatasource** in _Design view_
6) Remove the HomePage in the menu and let the child link be visible: <asp:SiteMapDataSource ID="SiteMapDataSource1" runat="server" **ShowStartingNode ="false"**/> _(MasterPage.master)_
