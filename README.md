Ext.ux.grid.feature.Searching
=============================

Search plugin for Ext.grid.Panel.


Usage
=====

`var searching = {
   ftype: 'searching',
   minChars: 2,
   mode: 'local'
}
var grid = Ext.create('Ext.grid.Panel', {
    store: store,
    stateful: true,
    stateId: 'stateGrid',
	features: [searching],
    columns: [{
      text      : 'Company',
      flex      : 1,
      sortable  : false,
      dataIndex : 'company'
   }, {
      text      : 'Unsearchable',
      flex      : 1,
      sortable  : false,
      dataIndex : 'unsearchable',
      searchable: false
   }]
})`


Links
=====
See ExtJS forum thread:

  http://www.sencha.com/forum/showthread.php?23615-Grid-Search-Plugin/page99


History
=======
Based on Ext.ux.grid.Search developed by Ing. Jozef Sakalos.

Converted to Ext 4 by Nathan LeBlanc.

Forum patches applied by Berend de Boer.
