Improved-Catalogsearch
======================

Improved catalogsearch for magento forked from Mikkel Ricky's improved catalogsearch

After you install the "improved catalogsearch" module. You can make changes to the weight of each individual attribute from System > Configuration > Catalog > Catalog Search Weight. 

Lower values = more relevance.

For example, if SKU + Name are 100 and both Descriptions are 200 a search containing a SKU or partial name match should be higher up in the results vs matches with mentions of the sku or name in it's description.

Changes to the weights require a reindex of the catalogsearch index.

### Changes 12.09.2016:
 - Fixed table name for Magento 1.9.2.4
 - Added composer support
 - Added modman support