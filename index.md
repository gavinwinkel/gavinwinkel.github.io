<html>
<body>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = ''; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00D7b000000A2Lc',
				'chatbot',
				'https://mcdonaldsusa--dev.sandbox.my.site.com/ESWchatbot1683044753050',
				{
					scrt2URL: 'https://mcdonaldsusa--dev.sandbox.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://mcdonaldsusa--dev.sandbox.my.site.com/ESWchatbot1683044753050/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>



</body>
</html>