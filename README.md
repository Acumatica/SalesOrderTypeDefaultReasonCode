[![Project Status](http://opensource.box.com/badges/active.svg)](http://opensource.box.com/badges)

Adding default reason code by sales order type to track revenue by Order Type.
==================================
An extension that allows to add default reason code by sales order type.

###Prerequisites
* Acumatica 5.30 or higher

Quick Start
-----------

### Installation

##### Install the customization deployment package
1. Download PXReasonCodeCustomizationExtensions.zip from this repository
2. In your Acumatica ERP instance, navigate to System -> Customization -> Customization Projects (SM204505), import PXReasonCodeCustomizationExtensions.zip as a customization project
3. Publish the customization project.

### Configuration

1. Go to Attributes Screen (CS211000) and create a new reason code along with Sales Sub if you need to.
![Screenshot](/_ReadMeImages/CS211000.png)

2. Navigate to Order Types Screen (SO201000) and select the Order Type for which you need to specify the reason code. Specify the Combine Sales Sub From and Reason Code fields.
![Screenshot](/_ReadMeImages/SO201000.png)

3. Navigate to Sales Orders Screen (SO301000), select the configured Order Type, add the sub account column to the grid if needed (hidden by default). When you add a document with an Inventory ID you should be able to see the default reason code and the Sub Acount fields already populated.
![Screenshot](/_ReadMeImages/SO301000.png)

Known Issues
------------
None at the moment

## Copyright and License

Copyright © `2017` `Acumatica`

This component is licensed under the MIT License, a copy of which is available online [here](LICENSE.md)

