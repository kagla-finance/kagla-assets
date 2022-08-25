# Display the Token Icon

In this page, you can find the steps to display the token icon of the pool you created.

## Create a pool in Kagla Factory
Follow [this guide]() to create a pool.



Token icons will be displayed on the Kagla UI by following the steps below.

Please note that it may take some time to reflect the icons due to cash reasons or so.

## 1. Create a branch

Fork this repository by creating a branch following the format; `assets/{Pool Address}`

It is desirable to fork it with the organization that is managing the token. (This is not mandatory.)

## 2. Commit the icon image file

Set the file name as `{token contract address}.png` and commit it to `/kagla-assets/images`

e.g.) `/kagla-asses/images/0x00d41391b0d455fdad49bc6fb8f590db844403b6.png`

### Detail of the requirement for the image file

for token

   - file name should be : `{token contract address}.png`
   - file type : PNG
   - square
   - bigger than 640x640px
   - regular circle

for LP token

   - file name should be : `{pool contract address}.png`
   - file type : PNG
   - square
   - bigger than 640x640px
   - regular circle
   - Background color: red
   - Outer frame color: black
   - icon color: black


## 3. Create a pull request

Please follow the template below
```
Pool URL: 
Token URL(Blockscout): 
Contact
Twitter:
Discord:
```
