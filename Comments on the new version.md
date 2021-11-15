- About the three main blocks (email, chat and phone) I understand the're links, a "mailto:", a normal link, and a "tel:" link. I don't have enought info about this to fullfill the link tag.

- In order to use Roboto font we have to import the font using a link. I'm not sure if this is gonna work properly oon the email clients. I provide fall back to the fonts used in the body section

- I would change the phone picture to the outline version to keep the same  style as in the other two. But I just realised the outlined version is only in FontAwesome PRO so it's not free. See: https://fontawesome.com/v5.15/icons/phone-alt?style=regular . 

- Also the phone pic seem always to be alitte bigger that the other two but it's just because the phone actualy uses the whole height of the pic while the other two have a more landscape format. I could manually correct this to make it look more like the others. Or we could find a completly different pic for the phone

- I'm a little worried about the spam filters because the desing uses bold fonts (weight 500 and 700) everywhere exect in the confidentiality notice

- Same thing for the pictures, I included the png version because I understant the svg wouldn't work

- The design is responsive to the window size. The elements will go from being in a row to be in a column as the windows shirks. In very wide windows the 3 elements will remain in the center (as in flex display with space-around).The pictures and the font-sizes will remain the same.

- All the styling is applied inline for each element so there should be no interference with the styles difined for the rest of the email template. However further future changes in the email template might affect the footer too as the're all in the same document.

- The template made use of some deprecated html attributes for the tables specifically "border" and "align". I change this for the corresponding CSS properties to guarante future compilance.

- I don't understand why the content cell (where "{{content}}" is located )uses colspan=3. Since it may be related with the content I decided to keep it and applied also in the rest of the table.

- The confidentiality notice is always kept centered and with a maximun with of 800px 

- The minimun window width would be around 250px which should be enought for any device or window

- I check all the css and html used to be compilant with css 1 or 2.Basically I didn't use anything that wasn't already in the old version