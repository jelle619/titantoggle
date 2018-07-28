# Titan Toggle

Titan Toggle adds a customisable button to your web page. You can make it open your chat when you click on it.
This project

## Setup
This project comes in two flavours. For each flavour, the setup differs slightly.

### Bootstrap flavour
![Bootstrap flavour demo](https://i.imgur.com/iDLmTG5.png)
This flavour is in alpha and can be embedded into your onto your site. To start, reference the two library files in the header of your page like.
```html
<link rel="stylesheet" href="https://cdn.rawgit.com/jelle619/titanbutton/5fedaf0b/Libraries/bootstrap-iso.css">
<script src="https://cdn.rawgit.com/jelle619/titanbutton/5fedaf0b/Libraries/bootstrap-iso.js"></script>
<link rel="stylesheet" href="https://cdn.rawgit.com/jelle619/titanbutton/5fedaf0b/style.css">
```

Then, paste the following code in the body of your website's HTML document. Make sure to replace "GUILD_URL_HERE" with the direct URL of your embed which can be found on your dashboard. It will not work otherwise!
```html
<div class="bootstrap-iso">
    <div id="TitanButtonEmbed">
        <div class="container">
            <button type="button" id="TitanButton" class="btn btn-info btn-lg" data-toggle="modal" data-target="#TitanModal"><img id="TitanIcon" src="https://github.com/TitanEmbeds/Titan/raw/master/webapp/titanembeds/static/img/titanembeds_shield.png" alt="Titan Embeds icon" srcset="https://cdn.rawgit.com/TitanEmbeds/Titan/bc129289/webapp/titanembeds/static/img/titanembeds-shield-white.svg"></button>
            <div class="modal fade" id="TitanModal" role="dialog">
                <div class="modal-dialog">
                    <div class="modal-content">
                        <div class="modal-body">
                            <div class="embed-container">
                                <iframe id="TitanIframe" src='GUILD_URL_HERE'></iframe>
                            </div>
                        </div>
                        <div class="modal-footer">
                            <button type="button" id="TitanCloseButton" class="btn btn-default" data-dismiss="modal"></button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
```

You may also use the minified version of this code.

```html
<div class="bootstrap-iso"> <div id="TitanButtonEmbed"> <div class="container"> <button type="button" id="TitanButton" class="btn btn-info btn-lg" data-toggle="modal" data-target="#TitanModal"><img id="TitanIcon" src="https://github.com/TitanEmbeds/Titan/raw/master/webapp/titanembeds/static/img/titanembeds_shield.png" alt="Titan Embeds icon" srcset="https://cdn.rawgit.com/TitanEmbeds/Titan/bc129289/webapp/titanembeds/static/img/titanembeds-shield-white.svg"></button> <div class="modal fade" id="TitanModal" role="dialog"> <div class="modal-dialog"> <div class="modal-content"> <div class="modal-body"> <div class="embed-container"> <iframe id="TitanIframe" src='GUILD_URL_HERE'></iframe> </div></div><div class="modal-footer"> <button type="button" id="TitanCloseButton" class="btn btn-default" data-dismiss="modal"></button> </div></div></div></div></div></div></div>
```

Congratulations! Your button has now been embedded onto your site!

### Material flavour
This button is in development and is not yet ready to be implemented! Feel free to contribute to it in the meantime.
