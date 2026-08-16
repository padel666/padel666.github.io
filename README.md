# PADEL666

## GitHub upload
Upload these items to the repository root:
- `index.html`
- `rackets.csv`
- `images/`

## Contact settings
Open `index.html` and search for:

`CONTACT SETTINGS`

Then replace:
- `YOUR_EMAIL_HERE@example.com`
- `VINTED_URL="#"`
- `WHATSAPP_URL="#"`

## Language
The site opens in **Hungarian by default**.
Visitors can switch to English with `HU | EN`.
The selected language is remembered in their browser.

## Updating products
Keep your master list in Google Sheets if you want, export it as CSV, and replace `rackets.csv`.

Keep the exact 19-column structure:
id,brand,model,status,condition,weight,shape,balance,price_huf,previous_owner,country,player_level,description_hu,description_en,image1,image2,image3,image4,image5

`available` = full product
`sold` = image + model + SOLD only
