
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DdL00000OF3ML',
				'ESA_Web_Deployment',
				'https://orgfarm-febb47d19f-dev-ed.develop.my.site.com/ESWESAWebDeployment1724800920657',
				{
					scrt2URL: 'https://orgfarm-febb47d19f-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://orgfarm-febb47d19f-dev-ed.develop.my.site.com/ESWESAWebDeployment1724800920657/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

    
</body>
</html>
