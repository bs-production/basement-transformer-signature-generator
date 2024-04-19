<template>
  <div>
      <section>
        <table cellpadding="0" cellspacing="0" border="0" style=
        "background: none; border-width: 0px; border: 0px; margin: 0; padding: 0;">
        <tr>
            <td valign="top" style="padding-top: 0; padding-bottom: 0; padding-left: 0; padding-right: 7px; border-top: 0; border-bottom: 0: border-left: 0;">
              <a href="https://www.thebasementtransformer.com">
                <img v-show="mobilePhoneSwitch" width="220" height="139" style="width: 220px; max-width: 220px !important; height: 139px; max-height: 139px !important; margin-top: 5px;" id="preview-image-url" src="https://cdn.treehouseinternetgroup.com/cms_images/1395/signature-logo-bar-basement-transformer.png" name="preview-image-url" />
        
                <img v-show="!mobilePhoneSwitch" width="190" height="121" style="width: 190px; max-width: 190px !important; height: 121px; max-height: 121px !important; margin-top: 5px;" id="preview-image-url" src="https://cdn.treehouseinternetgroup.com/cms_images/1395/signature-logo-bar-basement-transformer.png" name="preview-image-url" />
              </a>
            </td>
            
            <td style=
            "padding-top: 0; padding-bottom: 0; padding-left: 5px; padding-right: 0;">
            <table cellpadding="0" cellspacing="0" border="0" style=
            "background: none; border-width: 0px; border: 0px; margin: 0; padding: 0;">
              <tr>
                  <td colspan="2" style=
                  "padding-bottom: 5px; color: #F01014; font-size: 18px; font-family: Arial, Helvetica, sans-serif;">
                  {{fullName}}
                  </td>
                </tr>
                <tr>
                  <td colspan="2" style=
                  "color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  <em>{{title}}</em>
                  </td>
                </tr>
              <div v-show="!mobilePhoneSwitch">

              </div>
             
                <tr>
                  <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #F01014; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  Office:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  {{phone}}
                  </td>
                </tr>
                <tr v-show="mobilePhoneSwitch">
                <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #F01014; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  Mobile:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  {{mobilePhone}}
                  </td>
                </tr>
                <tr>
                    <td width="20" valign="top" style=
                    "vertical-align: top; width: 20px; color: #F01014; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                    Email:
                    </td>
                    <td valign="top" style=
                    "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                    <a :href="`mailto:${this.email}`" style="color: #333333; text-decoration: none; font-weight: normal; font-size: 14px;">{{email}}</a>
                      &nbsp;&nbsp;
                    </td>
                  </tr>
                <tr>
                  <td width="20" valign="top" style=
                  "vertical-align: top; width: 20px; color: #F01014; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  Web:
                  </td>
                  <td valign="top" style=
                  "vertical-align: top; color: #333333; font-size: 14px; font-family: Arial, Helvetica, sans-serif;">
                  <a href="https://www.thebasementtransformer.com" style=
                  "color: #333333; text-decoration: none; font-weight: normal; font-size: 14px;">
                  thebasementtransformer.com</a>
                    &nbsp;&nbsp;
                  </td>
                </tr>

                <tr>
                  <td colspan="2" style="padding-top: 5px;">
                    <a href="https://www.facebook.com/BasementTransformerNY" style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/facebook.png" /></a>
                    
                    <a href="https://www.google.com/maps/place/The+Basement+Transformer/@41.5870984,-74.3160776,9z/data=!3m1!4b1!4m6!3m5!1s0x89dcd4a4f559fb31:0xb73b0132e21e52ee!8m2!3d41.5870984!4d-74.3160776!16s%2Fg%2F11g6hr11b3?entry=ttu" style=
                    "border-width:0px; border:0px; text-decoration: none;"><svg id="icon-google" role="presentation" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 20 20"><path fill="currentColor" fill-rule="evenodd" d="M17.6 8.5h-7.5v3h4.4c-.4 2.1-2.3 3.5-4.4 3.4c-2.6-.1-4.6-2.1-4.7-4.7c-.1-2.7 2-5 4.7-5.1c1.1 0 2.2.4 3.1 1.2l2.3-2.2C14.1 2.7 12.1 2 10.2 2c-4.4 0-8 3.6-8 8s3.6 8 8 8c4.6 0 7.7-3.2 7.7-7.8c-.1-.6-.1-1.1-.3-1.7z" clip-rule="evenodd"></path></svg></a>
                    
                    <!-- <a href="https://www.youtube.com/channel/UCop6hiVtGvTDem0UqPppINw"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/youtube.png" /></a> -->
<!-- 
                    <a href="https://www.instagram.com/thebasementtransformer/"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/1874/instagram.png" /></a>

                    <a href="https://twitter.com/thebasementtransformer"
                    style=
                    "border-width:0px; border:0px; text-decoration: none;"><img width="25"
                    height="25" style=
                    "border: none; width: 25px; max-width: 25px !important; height: 25px; max-height: 25px !important;"
                    src=
                    "https://dc69b531ebf7a086ce97-290115cc0d6de62a29c33db202ae565c.ssl.cf1.rackcdn.com/169/twitter-icon.png" /></a> -->
                  </td>
                </tr>
              </table>
            </td>
          </tr>
        </table>
          <!-- <p style="font-size: 10px; color: #000; line-height: 12px;text-align: left; width: 450px" width="450">This message contains confidential information and is intended only for the intended recipients. If you are not an intended recipient you should not disseminate, distribute or copy this e-mail. Please notify us immediately by e-mail if you have received this e-mail by mistake and delete this e-mail from your system. E-mail transmission cannot be guaranteed to be secure or error-free as information could be intercepted, corrupted, lost, destroyed, arrive late or incomplete, or contain viruses. Therefore we do not accept liability for any errors or omissions in the contents of this message, which arise as a result of e-mail transmission. If verification is required please request a hard-copy version.</p> -->
    </section>
  </div>
</template>
<script>
export default {
  name: 'outputSignature',
  props: {
    fullName: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    mobilePhone: {
      type: String,
      required: true
    },
    phone: {
      type: String,
      required: true
    },
    email: {
      type: String,
      required: true
    },
    mobilePhoneSwitch: {
      type: Boolean,
      required: true
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #F01014;
}
</style>
