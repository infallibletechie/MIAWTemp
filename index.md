<html xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink">
    <head>
      <title>Messaging</title>
    </head>
    <body>        
        <script type='text/javascript'>         
            window.addEventListener("onEmbeddedMessagingReady", () => {
                console.log("onEmbeddedMessagingReady emitted");
            });
            window.addEventListener("onEmbeddedMessagingWindowMaximized", (e) => {
                console.log("Received the onEmbeddedMessagingWindowMaximized event…" + JSON.stringify(e.detail));
            });
	    window.addEventListener("onEmbeddedMessagingWindowMinimized", (e) => {
                console.log("Received the onEmbeddedMessagingWindowMinimized event…" + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingButtonClicked", (e) => {
                console.log("Received the onEmbeddedMessagingButtonClicked event…" + JSON.stringify(e.detail));
            });
	    window.addEventListener("onEmbeddedMessagingConversationRouted", (e) => {
                console.log("Received the onEmbeddedMessagingConversationRouted event…" + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingConversationStarted", (e) => {
                console.log("Received the onEmbeddedMessagingConversationStarted event…" + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingPreChatLoaded", (e) => {
                console.log("Received the onEmbeddedMessagingPreChatLoaded event…" + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingPreChatSubmitted", (e) => {
                console.log("Received the onEmbeddedMessagingPreChatSubmitted event…" + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingConversationParticipantChanged", (e) => {
                var eventName = "onEmbeddedMessagingConversationParticipantChanged";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessageSent", (e) => {
                var eventName = "onEmbeddedMessageSent";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingTranscriptRequested", (e) => {
                var eventName = "onEmbeddedMessagingTranscriptRequested";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
	    window.addEventListener("onEmbeddedMessagingTranscriptRequestFailed", (e) => {
                var eventName = "onEmbeddedMessagingTranscriptRequestFailed";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingTranscriptDownloadSuccessful", (e) => {
                var eventName = "onEmbeddedMessagingTranscriptDownloadSuccessful";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessagingConversationClosed", (e) => {
                var eventName = "onEmbeddedMessagingConversationClosed";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessageDelivered", (e) => {
                var eventName = "onEmbeddedMessageDelivered";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
            window.addEventListener("onEmbeddedMessageRead", (e) => {
                var eventName = "onEmbeddedMessageRead";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
	   window.addEventListener("onEmbeddedMessagingLinkClicked", (e) => {
                var eventName = "onEmbeddedMessagingLinkClicked";
                console.log(`Received the ${eventName} event…` + JSON.stringify(e.detail));
            });
        </script>
<script type='text/javascript'>
	function initEmbeddedMessaging() {
		try {
			embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

			embeddedservice_bootstrap.init(
				'00DWs0000032Xm9',
				'MIAW',
				'https://infallibletechie4-dev-ed.develop.my.site.com/ESWMIAW1724880016303',
				{
					scrt2URL: 'https://infallibletechie4-dev-ed.develop.my.salesforce-scrt.com'
				}
			);
		} catch (err) {
			console.error('Error loading Embedded Messaging: ', err);
		}
	};
</script>
<script type='text/javascript' src='https://infallibletechie4-dev-ed.develop.my.site.com/ESWMIAW1724880016303/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

    </body>
  </html>
