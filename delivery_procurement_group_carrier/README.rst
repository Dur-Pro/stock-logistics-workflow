==================================
Delivery Procurement Group Carrier
==================================

.. 
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! This file is generated by oca-gen-addon-readme !!
   !! changes will be overwritten.                   !!
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
   !! source digest: sha256:b30e0ed690a160f85899c495459a1e6b98e9e99035f1efc711676b379c12f44f
   !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!

.. |badge1| image:: https://img.shields.io/badge/maturity-Beta-yellow.png
    :target: https://odoo-community.org/page/development-status
    :alt: Beta
.. |badge2| image:: https://img.shields.io/badge/licence-AGPL--3-blue.png
    :target: http://www.gnu.org/licenses/agpl-3.0-standalone.html
    :alt: License: AGPL-3
.. |badge3| image:: https://img.shields.io/badge/github-OCA%2Fstock--logistics--workflow-lightgray.png?logo=github
    :target: https://github.com/OCA/stock-logistics-workflow/tree/17.0/delivery_procurement_group_carrier
    :alt: OCA/stock-logistics-workflow
.. |badge4| image:: https://img.shields.io/badge/weblate-Translate%20me-F47D42.png
    :target: https://translation.odoo-community.org/projects/stock-logistics-workflow-17-0/stock-logistics-workflow-17-0-delivery_procurement_group_carrier
    :alt: Translate me on Weblate
.. |badge5| image:: https://img.shields.io/badge/runboat-Try%20me-875A7B.png
    :target: https://runboat.odoo-community.org/builds?repo=OCA/stock-logistics-workflow&target_branch=17.0
    :alt: Try me on Runboat

|badge1| |badge2| |badge3| |badge4| |badge5|

This is a base module that propagates the SO carrier to the procurement
group.

Having the carrier on the procurement group allows to apply different
routing for each carrier thanks to the dynamic routing. A rule domain
can then be expressed based on the delivery carrier. See the module
stock_dynamic_routing in OCA/wms.

The carrier on the procurement group is also used for grouping several
SO in a same delivery by carrier. See the module
stock_picking_group_by_partner_by_carrier in this repository.

**Table of contents**

.. contents::
   :local:

Bug Tracker
===========

Bugs are tracked on `GitHub Issues <https://github.com/OCA/stock-logistics-workflow/issues>`_.
In case of trouble, please check there if your issue has already been reported.
If you spotted it first, help us to smash it by providing a detailed and welcomed
`feedback <https://github.com/OCA/stock-logistics-workflow/issues/new?body=module:%20delivery_procurement_group_carrier%0Aversion:%2017.0%0A%0A**Steps%20to%20reproduce**%0A-%20...%0A%0A**Current%20behavior**%0A%0A**Expected%20behavior**>`_.

Do not contact contributors directly about support or help with technical issues.

Credits
=======

Authors
-------

* Camptocamp
* BCIM

Contributors
------------

-  Camptocamp:

   -  Alexandre Fayolle <alexandre.fayolle@camptocamp.com>
   -  Thierry Ducrest <thierry.ducrest@camptocamp.com>

-  BCIM:

   -  Jacques-Etienne Baudoux <je@bcim.be>

-  TROBZ:

   -  Phuc Tran Thanh <phuc@trobz.com>

-  Denis Roussel <denis.roussel@acsone.eu>
-  `APSL <https://apsl.tech>`__:

   -  Antoni Marroig <amarroig@apsl.net>

Other credits
-------------

The development of this module has been financially supported by:

-  Camptocamp

Maintainers
-----------

This module is maintained by the OCA.

.. image:: https://odoo-community.org/logo.png
   :alt: Odoo Community Association
   :target: https://odoo-community.org

OCA, or the Odoo Community Association, is a nonprofit organization whose
mission is to support the collaborative development of Odoo features and
promote its widespread use.

This module is part of the `OCA/stock-logistics-workflow <https://github.com/OCA/stock-logistics-workflow/tree/17.0/delivery_procurement_group_carrier>`_ project on GitHub.

You are welcome to contribute. To learn how please visit https://odoo-community.org/page/Contribute.
