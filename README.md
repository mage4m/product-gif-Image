# m2-mage4-EnableGif
Manually:

Copy the zip into app/code/Mage4/EnableGIF directory


#### After installation by either means, enable the extension by running following commands:

sudo php bin/magento setup:upgrade
sudo php bin/magento setup:di:compile
sudo php bin/magento setup:static-content:deploy -f
sudo php bin/magento cache:flush


About Extension:
	It will allow to render .Gif Images for product. Just add .gif images form backend in product listing. 