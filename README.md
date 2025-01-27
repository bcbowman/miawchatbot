# Agentforce Test Bot
<style type='text/css'>
        .embeddedServiceHelpButton .helpButton .uiButton {
            background-color: #ceff85;
        font-family: "Arial", sans-serif;
            color: #000;
        }
        .embeddedServiceHelpButton .helpButton .uiButton:focus {
                outline: 1px solid #597d22;
        }

        .embeddedMessagingConversationButton{
            background-color: #84d709;
        }
    </style>

 <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DOu000005wSx7',
				'Messaging_Deployment',
				'https://goosehead--miaw.sandbox.my.site.com/ESWMessagingDeployment1737308905282',
				{
					scrt2URL: 'https://goosehead--miaw.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://goosehead--miaw.sandbox.my.site.com/ESWMessagingDeployment1737308905282/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>
