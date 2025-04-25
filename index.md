<html>

    <body>
        <script type='text/javascript'>
        function initEmbeddedMessaging() {
            try {
                embeddedservice_bootstrap.settings.language = 'en_US'; // For example, enter 'en' or 'en-US'

                embeddedservice_bootstrap.init(
                    '00DdL00000OF3ML',
                    'Developer_CodeLive',
                    'https://orgfarm-febb47d19f-dev-ed.develop.my.site.com/ESWDeveloperCodeLive1745500612405',
                    {
                        scrt2URL: 'https://orgfarm-febb47d19f-dev-ed.develop.my.salesforce-scrt.com'
                    }
                );
            } catch (err) {
                console.error('Error loading Embedded Messaging: ', err);
            }
        };
    </script>
    <script type='text/javascript' src='https://orgfarm-febb47d19f-dev-ed.develop.my.site.com/ESWDeveloperCodeLive1745500612405/assets/js/bootstrap.min.js' onload='initEmbeddedMessaging()'></script>

        
    </body>
