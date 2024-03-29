# Build An Alexa Color Picker Skill using ASK Python SDK
<img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/quiz-game/header._TTH_.png" />

[![Voice User Interface](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/1-locked._TTH_.png)](./1-voice-user-interface.md)[![Lambda Function](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/2-locked._TTH_.png)](./2-lambda-function.md)[![Connect VUI to Code](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/3-locked._TTH_.png)](./3-connect-vui-to-code.md)[![Testing](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/4-locked._TTH_.png)](./4-testing.md)[![Customization](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/5-locked._TTH_.png)](./5-customization.md)[![Publication](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/6-on._TTH_.png)](./6-publication.md)

## Get Your Skill Certified and Published

We are almost done!  The last step is to add the metadata that your skill will use in the [Skill Store](http://amazon.com/skills).  This page will walk you through the remaining steps to launch your skill!

1. Select the **Distribution** tab from the top navigation menu.

2. Fill out the form fields per the guidance on the screen. Hover over the question mark icons for details regarding each respective field. **Fields marked with an Asterisk, are required!**
	* Take the time to get these right so that your skill will pass certification!

3.  **Write your skill descriptions.**

       *  **Spend some time coming up with an enticing, succinct description.**  This is one of the few places you have an opportunity to attract new users, so make the most of it!  These descriptions show up in the list of skills available in the [Alexa app](http://alexa.amazon.com/spa/index.html#skills) and the [skills store](http://www.amazon.com/skills).

4.  For your example phrases, **come up with the three most exciting ways** a user can talk to your skill.

    *  Make sure that each of your example phrases are a **perfect match with one of your Sample Utterances.**  Incorrect example phrases are one of the most common reasons that skills fail certification, so we have provided a short list of things to consider as you write your example phrases:

       | Common Failure Points for Example Phrases |
       | ----------------------------------------- |
       | Example phrases **must** adhere to the [supported phrases](https://developer.amazon.com/public/solutions/alexa/alexa-skills-kit/docs/supported-phrases-to-begin-a-conversation?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=howto-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_howto-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs). |
       | Example phrases **must** be based on sample utterances specified in your Intent Schema. |
       | Your first example phrase **must** include a wake word and your invocation name. |
       | Example phrases **must** provide a contextual response. |

    *  Choose three example phrases that are likely to be the most common ways that users will attempt to interact with your skill. Make sure that each of them works well, and provides an excellent user experience.

5. Choose the most appropriate category for your skill.

6.  Provide a comprehensive list of **keywords** for users that are searching for new skills.  This is an optional field, and searching the [Alexa app](http://alexa.amazon.com) or the [skill store](http://www.amazon.com/skills) will also find the words in your Skill Name and descriptions, so you don't need to overdo it.  That being said, if there are words that you want users to find your skill with, you should include them here.  Separate the keywords with commas.

7. **Privacy Policy URL.** This is an optional field, and should not be required for this How TO skill sample.  You can leave it blank.

8. **Terms of Use URL.** This is also optional, and you can leave it blank.

9.  **Create your skill's icons.**  You need two sizes of your icon: 108x108px and 512x512px.

    *  Make sure you have the rights to the icons you create. Please don't violate any trademarks or copyrights.
    *  You can use the **Alexa skill icon builder [tool](https://developer.amazon.com/docs/tools/icon-builder.html).**
    *  If you don't have software to make icons, try one of these free options:

       *  [GIMP](https://www.gimp.org/) (Windows/Mac/Linux)
       *  [Canva](https://www.canva.com/) (Web)
       *  [Paint.NET](http://www.getpaint.net/index.html) (Windows)
       *  [Inkscape](http://inkscape.org) (Windows/Mac/Linux)
       *  [Iconion](http://iconion.com/) (Windows/Mac)

    *  To make it easier to get started, we've created blank versions of these icons in both sizes for many formats:

       *  [PSD](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/psd._TTH_.zip)
       *  [PNG](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/png._TTH_.zip)
       *  [GIF](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/gif._TTH_.zip)
       *  [PDF](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/pdf._TTH_.zip)
       *  [JPG](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/jpg._TTH_.zip)
       *  [SVG](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/svg._TTH_.zip)
       *  [PDN](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/pdn._TTH_.zip) - for [Paint.NET](http://www.getpaint.net/index.html)
       *  [XCF](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/icon-templates/xcf._TTH_.zip) - for [GIMP](https://www.gimp.org/)

10. When you're ready, click **Save and Continue** at the bottom of the screen to move onto **Privacy & Compliance**

11. *  **Does this skill allow users to make purchases or spend real money?** For this skill, the answer is no.  For future skills, make sure you answer this appropriately.

    *  **Does this skill use Alexa Shopping Actions?** Again, for this skill, the answer is no.

    *  **Does this Alexa skill collect users' personal information? (e.g., anything that can identify the user)** Again, for this skill, the answer is no.  If you do collect information about a user, such as names, email addresses, phone numbers, and so forth, ensure that you answer Yes to this question.
        *  Answering "yes" to this question will also require you to provide a link to your Privacy Policy at the bottom of the page.

    *  **Is this skill directed to or does it target children under the age of 13?** Because you customized this skill with data you provided, it is possible that you created a skill that targets children under the age of 13.  For this skill, the answer is **no** because it doesn't target a specific age group.
        * Factors to consider in determining if this skill is directed to children under 13 include:
            * Subject matter of the skill
            * Presence of child-oriented activities and incentives
            * Type of language used in the skill
            * Music and other audio content in the skill
            * How the skill is described and marketed
            * Intended audience for the skill

            If you're not sure, please see the [FTC's COPPA Guidance and FAQ](https://www.ftc.gov/tips-advice/business-center/guidance/complying-coppa-frequently-asked-questions) for more information.

12.  **Export Compliance.** Be certain that you agree with all of the conditions.  If you do, make sure to check this box, as Amazon requires this permission to distribute your skill around the globe.  

13. **Provide testing instructions.** Testing instructions give you an opportunity to explain your skill, and any special or possibly confusing features, to the certification team.  A value is required in this box.

	* Since this skill is not using Account Linking, you don’t need to provide ‘Username’ and ‘Password’ for testing the skill.

	* Since you are using our Sample, make sure to add a sentence to your Testing Instructions referencing the Sample you used. For example:

           ```
           This was built using the Color Picker Sample.
           ```

           This will let the testing team understand what you're providing them, and should decrease the testing time required.    

	**Note:** More details on certification are [available here.](https://alexa.design/certification)

14. Click **Save and Continue** at the bottom of the screen to move onto **Availability**

15. *  Can your skill be used by everyone or is it targeted to select businesses?For this skill, the answer is Public.

    *  **Beta Test** If you want your skill to be beta tested by others, before publishing it to public.
    
    *  **Skill availability in regions** Can Amazon distribute your skill in all regions or you use some region specific features in your skill. For this skill, the answer is all countries.	

16. If you feel that your skill is ready for certification, click the **Save and Continue** button at the bottom of the page.

17. Run through the **Validation**, **Functional Test** and work on any fixes that are suggested during the initial review.

18. Once you are good with the tests, click the **Submission** tab and **Submit for review** button.

19. **You're done with your submission!**  Here are a few things you might need to know:

    *  **Certification can take several days to complete.** Please be patient.  It takes time because we want to get it right.

    *  **Did something go wrong?** The evangelists team run [online office hours every Tuesday from 9-10am Pacific Time](https://alexa.design/officehours).  They can help answer any questions you might have.

    *  **Want the coolest t-shirt you've ever seen?** Every month, we create a brand-new Alexa Developer t-shirt or hoodie, and send them out to developers that published a skill that month.  [You can get yours here if you live in the US](https://developer.amazon.com/alexa-skills-kit/alexa-developer-skill-promotion?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs), [here for the UK](https://developer.amazon.com/en-gb/alexa-skills-kit/alexa-developer-skill-promotion?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs), [here for Germany](https://developer.amazon.com/de-de/alexa-skills-kit/alexa-developer-skill-promotion?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs), [here for India](https://developer.amazon.com/alexa-skills-kit/alexa-developer-skill-promotion-india?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs), [here for Japan](https://developer.amazon.com/ja/alexa-skills-kit/alexa-developer-skill-promotion?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs), [here for France](https://developer.amazon.com/fr/alexa-skills-kit/alexa-developer-skill-promotion?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs), and [here for Australia](https://developer.amazon.com/anz/alexa-skills-kit/alexa-developer-skill-promotion?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=fact-nodejs-V2_GUI-6&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_fact-nodejs-V2_GUI-6_Convert_WW_beginnersdevs&sc_segment=beginnersdevs).
