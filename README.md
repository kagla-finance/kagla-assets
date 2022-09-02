# Display the Token Icon

In this page, you can find the steps to display the token icon of the pool you created.

## Create a pool in Kagla Factory
Follow [this guide](https://docs.kagla.finance/pool/kagla-factory) to create a pool.



Token icons will be displayed on the Kagla Finance UI by following the steps below.

Please note that it may take some time to reflect the icons due to cash reasons or so.

## 1. Create a branch

Fork this repository by creating a branch following the format; `assets/{Pool Address}`

To get pool address, first you need to jump to [this page](https://kagla.finance/app/pools) and click the pool you created. Once you get to the page of the pool you created, the string following "https://kagla.finance/app/pools/" in the URL is the pool address.

It is mandatory to fork it with the organization that is managing the token. 
However, if you are creating a pool with token that you are not managing, we will contact you for some confirmation after you finish pushing a pull request.

## 2. Commit the icon image file

Set the file name as `{token contract address}.png` and commit it to `/kagla-assets/images`

e.g.) `/kagla-asses/images/0x00d41391b0d455fdad49bc6fb8f590db844403b6.png`

### Requirements for the image files

#### for tokens
   - file name should be : `{token contract address}.png` (All lowercase)
   - file type : PNG
   - square size bigger than 640 x 640px


[example1](https://github.com/kagla-finance/kagla-assets/blob/main/images/0xffffffff00000000000000010000000000000001.png) 
, [example2](https://github.com/kagla-finance/kagla-assets/blob/main/images/0xe511ed88575c57767bafb72bfd10775413e3f2b0.png) 
, [example3](https://github.com/kagla-finance/kagla-assets/blob/main/images/0x733ebcc6df85f8266349defd0980f8ced9b45f35.png) 

#### for LP tokens
   - file name should be : `{token contract address}.png` (All lowercase)
   - file type : PNG
   - square size bigger than 640 x 640px
   - icon in a regular circle
   - background color : #C93D4B
   - color of icon : #13070C
   - Outer frame requirements
      - color : #13070C
      - 10% of the total image size thickness
         - 100px for the image of 1000px as a whole
         - 64px for the image of 640px as a whole
     

[example1](https://github.com/kagla-finance/kagla-assets/blob/main/images/0xe12332a6118832cbafc1913ec5d8c3a05e6fd880.png) 
, [example2](https://github.com/kagla-finance/kagla-assets/blob/main/images/0x847f0fd7e3a234e7321d01ff2347e4501ea89cf1.png)
, [expample3](https://github.com/kagla-finance/kagla-assets/blob/main/images/0x00d41391b0d455fdad49bc6fb8f590db844403b6.png)


## 3. Create a pull request

Please follow the template below. (Template must be completed.)
```
Did you follow [this guide](https://github.com/kagla-finance/kagla-assets)?: Yes/No

Do the images you are uploading meet the requirements of the guide?: Yes/No

Pool URL: 

Token URL(Blockscout): 

Contact
 - Twitter:
 - Discord:
 
```
