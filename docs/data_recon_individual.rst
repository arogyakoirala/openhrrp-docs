Individual table
=============

Summary
-------

	1. This table contains information about individual members. The combination of howner_sn, house_sn, hhd_sn, mem_sn uniquely defines an individual family member for a house owner.
	2. The Birth registration is considered for the members having age<=5 years
	3. Education level is considered for the members having age>=5 years
	4. Martial status if considered for the members having age>=10 years
	5. Social security field is spread across 9 columns(security1 to security9) and filled with appropriate option that were applicable. Similar to other tables, further work in needed on this to make proper use of this. May be we can make use of flags rather than code numbers.

Results
-------

The table below outlines current status of the same:

.. csv-table::
   :file: _data/data_recon_individual/individualColNames.csv