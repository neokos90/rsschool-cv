# rsschool-cv
# Nekipelova Oksana
# My contact info:
* phone: +7 950-062-79-72
* e-mail: <oksana.bruys@gmail.com>
* GitHub: neokos90
* Telegram: <https://t.me/OksaBruys>

# About me
Web developer, I am engaged in the creation and maintenance of information systems that I want to use. I am not indifferent to problems that do not specifically concern me, but in general affect the result of the team's work. 

# Skills
* HTML, CSS(Bootstrap), JavaScript(JQuery)
* MySQL, Microsoft SQL Server
* PHP
* CMS Bitrix

# Code examples

    $(window).load(function() {
	    if (window.location.hash) {
            var hash = window.location.hash;
            const element = document.getElementById(hash.slice(1));

            if(element) {
                let position = element.offsetTop;
                let userAgent = window.navigator.userAgent;

                if(userAgent.match(/firefox|fxios/i))
                {
                    position = position - 100;
                }


                $('html, body').animate({
                    scrollTop: position
                }, 900, 'swing');
            }
	    }
    });

# Education
 * Irkutskiy gosudarstvennyy universitet 

 # Languages 
 * Russian - native speaker
 * English - B1