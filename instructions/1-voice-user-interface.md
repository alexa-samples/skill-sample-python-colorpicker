# Build An Alexa Color Picker Skill using ASK Python SDK
<img src="https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/quiz-game/header._TTH_.png" />

[![Voice User Interface](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/1-on._TTH_.png)](./1-voice-user-interface.md)[![Lambda Function](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/2-off._TTH_.png)](./2-lambda-function.md)[![Connect VUI to Code](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/3-off._TTH_.png)](./3-connect-vui-to-code.md)[![Testing](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/4-off._TTH_.png)](./4-testing.md)[![Customization](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/5-off._TTH_.png)](./5-customization.md)[![Publication](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/navigation/6-off._TTH_.png)](./6-publication.md)

## Setting up Your Alexa Skill in the Developer Console

1.  Go to the **[Alexa Developer Console](https://developer.amazon.com/alexa/console/ask)**. Enter your account credentials and click the **Sign In** button.
(If you don't already have an account, you will be able to create a new one for free.)

1.  Once you have signed in, select the **Create Skill** button near the top-right of the list of your Alexa Skills.

1. Give your new skill a **Name**, for example, 'Color Picker'. This is the name that will be shown in the Alexa Skills Store, and the name your users will refer to.

1. Select the Default Language.  This tutorial will presume you have selected 'English (US)'. Click the **Next** button at the top right.

1. Select **Other** under the *'Choose a type of experience'* section.

1. Select the **Custom** model under the *'Choose a model'* section.

1. Select **Provision your own** under the *'Hosting services'* section. Click the **Next** button at the top right.

1. Choose **Start from scratch** from the *Templates* section and click the **Next** button at the top right.

1. Review your selections and click the **Create Skill** button at the top right.

1. **Build the Interaction Model for your skill**
	1. On the left hand navigation panel, select the **JSON Editor** tab under **Interaction Model**. In the textfield provided, replace any existing code with the code provided in the [Interaction Model](../models/en-US.json).  Click **Save**.
    2. If you want to change the skill invocation name, select the **Invocations** tab on the left hand navigation panel. Select **Skill Invocation Name** and enter a **Skill Invocation Name**. This is the name that your users will need to say to start your skill.  In this case, it's preconfigured to be ‘my color picker'.
    3. Click **Save** and then **Build skill**.

	**Note:** You should notice that **Intents** and **Slot Types** will auto populate based on the JSON Interaction Model that you have now applied to your skill. Feel free to explore the changes here, to learn about **Intents**, **Slots**, and **Utterances** open our [technical documentation in a new tab](https://developer.amazon.com/docs/custom-skills/create-intents-utterances-and-slots.html?&sc_category=Owned&sc_channel=RD&sc_campaign=Evangelism2018&sc_publisher=github&sc_content=Survey&sc_detail=quiz-game-python-V2_GUI-1&sc_funnel=Convert&sc_country=WW&sc_medium=Owned_RD_Evangelism2018_github_Survey_quiz-game-python-V2_GUI-1_Convert_WW_beginnersdevs&sc_segment=beginnersdevs).

11. **Optional:** Select a custom intent by expanding the **Intents** from the left side navigation panel. Add some more sample utterances for your newly generated intents. Think of all the different ways that a user could request to make a specific intent happen. A few examples are provided. Be sure to click **Save** and **Build skill** after you're done making changes here.

12. If your interaction model builds successfully, proceed to the next step. If not, you should see an error. Try to resolve the errors. In our next step of this guide, we will be creating our Lambda function in the AWS developer console, but keep this browser tab open, because we will be returning here on [Page #3: Connect VUI to Code](./3-connect-vui-to-code.md).

     If you get an error from your interaction model, check through this list:

     *  **Did you copy & paste the provided code correctly?**
     *  **Did you accidentally add any characters to the Interaction Model?**

[![Next](https://m.media-amazon.com/images/G/01/mobile-apps/dex/alexa/alexa-skills-kit/tutorials/general/buttons/button_next_lambda_function._TTH_.png)](./2-lambda-function.md)
