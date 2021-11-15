# zendesk-theme
Template here:
    https://igerent.zendesk.com/agent/admin/email

Guidelines
    Do not use CSS3 style declarations. Stick to CSS1 or 2.
    Do not add more DIV sections.
----Keep text formatting to a minimum. Lots of bold text can trigger spam filters.
----Don't add lots of images (another trigger for spam filters) and downscale the images that you do use.
    Use the ALT tag on all images. The tag displays a description of the image before users allow the images to be displayed.
    If you know the width and height of the image, define it. This forces the email client to reserve the image space in the layout of the email before the images have been downloaded.
    Background images are not supported in all email clients, so don't rely on them for information or functional design.
    Don't link to images in a closed Zendesk. If the intended recipient is not a registered and signed-in user, the images will be broken.


Versions
    index.html: current test version
    live.html: the version that was copied from the live zendesk

Notes
    1-{{delimiter}} Since we are not using Mail delimiter we can remove the tag
    2-Before adding logos and other images, remember that most email clients don't display images by default.

Other Configurations
    100% Add the photo of the agent
    Personalized email replies
