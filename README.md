html lang="en-gb">
	<head><script src="/d-Headiction-our-How-and-ther-Lord-That-manly-sp" async></script>

    <title>The Official Pokémon Website | Pokemon.co.uk</title>


<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-V9L7');</script>
<!-- End Google Tag Manager -->


<link rel="shortcut icon" href="https://assets.pokemon.com/static2/_ui/img/favicon.ico"/>
<link rel="stylesheet" href="https://assets.pokemon.com/static2/_ui/css/main.css"/>
<link href="//fonts.googleapis.com/css?family=Roboto:400,700" rel="stylesheet" type="text/css" />

<script src="https://assets.pokemon.com/static2/_ui/js/vendor/modernizr.custom.js"></script>
    <script src="https://www.recaptcha.net/recaptcha/enterprise.js?render=6Lc4P0MoAAAAAAhyCYBhoVfHZUF3HMvFdXSRZ-kO&hl=en-gb"></script>


<script>
    // TODO: this should be moved to a better place in the application
    // needed for image deferred loading in sliders
    window.addEventListener('load', function () {
        window.loaded = true;
    });
</script>


<script>
    window.token = "4irb2DZnTqszXC3dKKW48KmSgGELh60QcW3VrBbRAo5bgwFIfDdCFypAvQvwR2SK";
    window.mockAPI = false;
    window.loginURL = '/uk/pokemon-trainer-club/login';
    window.pokemonUI = window.pokemonUI || {};

    window.pokemonUI.recaptcha_key = "6Lc4P0MoAAAAAAhyCYBhoVfHZUF3HMvFdXSRZ-kO";
    window.pokemonUI.email_signup_api = "https://api.emo.pokemon.com/";
    window.pokemonUI.countryCode = 'uk';
    window.pokemonUI.api = {
        'user-details': 'https://www.pokemon.com/api/users/details',
        'base-url-secure': 'https://www.pokemon.com',

        'gsa': '/us/search/api/'

    };

    window.pokemonUI.config = {
        'collection': 'production_pokemon_collection'
    };

    window.pokemonUI.modals = window.pokemonUI.modals || {};
    window.pokemonUI.modals = {
        "season": "Season",
        "episode": "Episode",
        "legal": "Notice: If you click on the YouTube video above, you will leave Pokemon.com. The Pokémon Company International is not responsible for the content of any linked website that is not operated by The Pokémon Company International. Please note that these websites' privacy policies and security practices may differ from The Pokémon Company International's standards.",

        "twitchlegal": "Notice: If you click on the Twitch video above, you will leave Pokemon.com. The Pokémon Company International is not responsible for the content of any linked website that is not operated by The Pokémon Company International. Please note that these websites' privacy policies and security practices may differ from The Pokémon Company International's standards.",
    };
    window.pokemonUI.dictionary = window.pokemonUI.dictionary || {};
    window.pokemonUI.dictionary.dashboard = {
        "youRecentlyPurchased": "You Recently Redeemed",
        "shopMore": "Shop More"
    };
    window.pokemonUI.global_dictionary = window.pokemonUI.global_dictionary || {};
    window.pokemonUI.global_dictionary.search = {
        'searchUrl': '/uk/search/',
        'GSALanguageCode': 'uk',
        'sortBy': 'Sort by:',
        'filterBy': 'Filter by:',
        'selectCategory': 'View All',
        'mostRelevant': 'Most Relevant',
        'mostRecent': 'Most Recent',
        'returnedResults': 'Returned XXXX Results',
        'recommendedResults': 'Recommended Results',
        'playGame': 'Play Game',
        'all': {title: 'View All'},
        'pokedex': {title: 'Pokédex'},
        'videogames': {title: 'Video Game'},
        'tcg': {title: 'Trading Card Game'},
        'funzone': {title: 'Online Game'},
        'animation': {title: 'Pokémon TV'},
        'news': {title: 'News'},
        'events': {title: 'Events'},
        'strategy': {title: 'Strategy'},

        "numberPrefix": "#"
    };
    window.pokemonUI.global_dictionary.datatables = {
        'search': 'Search:',
        'previous': 'Previous',
        'next': 'Next',
        'emptyTable': "No data is available.",
        'zeroRecords': "No matching records found."
    };
    window.pokemonUI.global_dictionary.errorMessages = {
        'dataError': 'Currently unavailable. Please try again.'
    };
    window.pokemonUI['ui-path'] = 'https://assets.pokemon.com/static2/_ui/'

    window.pokemonUI.global_api = {

        'gsa': '/us/search/api/',

        'status-indicators': {
            'game-server-status': '/api/tcg/game_server_status',
            'tcgo-in-maintenance': '/api/tcg/in_maintenance_status',
            'notifications': 'https://www.pokemon.com/api/user/notifications/config'
        }
    };

    window.pokemonUI.cookie = {
        set: function (name, value, days) {
            if (days) {
                var date = new Date();
                date.setTime(date.getTime() + (days * 24 * 60 * 60 * 1000));
                var expires = "; expires=" + date.toGMTString();
            } else var expires = "";
            document.cookie = name + "=" + value + expires + "; path=/";
        },

        get: function (name) {
            var nameEQ = name + '=',
                ca = document.cookie.split(';'),
                c, i = 0, ii = 0;

            for (i = 0, ii = ca.length; i < ii; i++) {
                c = ca[i];

                while (c.charAt(0) === ' ') {
                    c = c.substring(1, c.length);
                }

                if (c.indexOf(nameEQ) === 0) {
                    var value = c.substring(nameEQ.length, c.length);
                    if (value.charAt(0) == '"' && value.charAt(value.length - 1) == '"') {
                        value = value.substring(1, value.length - 1);
                    }
                    return value;
                }
            }
            return null;
        }
    };

    window.enableDashboard = true;

</script>
<link rel="stylesheet" href="https://assets.pokemon.com/static2/_ui/css/gus.css" media="all" type="text/css"/>
<link rel="stylesheet" href="https://assets.pokemon.com/static2/_ui/css/gus_integration.css"/>

                <link rel="alternate" hreflang="pt-br" href="https://www.pokemon.com/br" />
                <link rel="alternate" hreflang="es-xl" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-do" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-py" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-cl" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-gt" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-mx" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-hn" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-uy" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-bo" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-ar" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-cr" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-pe" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-co" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-pa" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="es-sv" href="https://www.pokemon.com/el" />
                <link rel="alternate" hreflang="de" href="https://www.pokemon.com/de" />
                <link rel="alternate" hreflang="es" href="https://www.pokemon.com/es" />
                <link rel="alternate" hreflang="it" href="https://www.pokemon.com/it" />
                <link rel="alternate" hreflang="en" href="https://www.pokemon.com/us" />
                <link rel="alternate" hreflang="fr" href="https://www.pokemon.com/fr" />
                <link rel="alternate" hreflang="en-gb" href="https://www.pokemon.com/uk" />
                <link rel="alternate" hreflang="ja" href="https://www.pokemon.com/jp/" />

<meta charset="utf-8"/>
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1"/>
<meta http-equiv="Content-Language" content="en-gb"/>
<meta name="language" content="en-gb"/>
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/>

<meta name="twitter:card" content="summary" />

<meta property="og:title" content="The Official Pokémon Website" />
<meta name="twitter:title" content="The Official Pokémon Website" />

<meta property="og:image" content="https://www.pokemon.com/static-assets/app/static3/img/og-default-image.jpeg" />
<meta name="twitter:image" content="https://www.pokemon.com/static-assets/app/static3/img/og-default-image.jpeg" />



    <meta property="og:description" content="The official source for Pokémon news and information on the Pokémon Trading Card Game, apps, video games, animation, and the Pokédex." />
    <meta name="twitter:description" content="The official source for Pokémon news and information on the Pokémon Trading Card Game, apps, video games, animation, and the Pokédex." />
    <meta name="pkm-description" content="The official source for Pokémon news and information on the Pokémon Trading Card Game, apps, video games, animation, and the Pokédex." />

    <meta name="pkm-modified-date" content="20240301" />

<link rel="canonical" href="https://www.pokemon.com/uk" />

        <link rel="stylesheet" href="https://assets.pokemon.com/static2/_ui/css/homepage.css" />


    </head>

    <body class="uk fluid custom-form-elements ">

<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-V9L7"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->

<div id='gus-wrapper'>
    <div class="pokemon-gus-container" data-site="pcom" data-locale="en-gb" data-api="/pcom/api/gus/" data-width="913px"></div>
</div>
<div class="main-filler"></div>


<nav class="main">

    <div class="blocker"></div>

    <div class="content-wrapper">

        <div class="nav-bar">
            <a href="#" class="nav-toggle"><span
                    class="icon icon_hamburger"></span></a>

            <ul class="dashboard-open visible-mobile">
                <li class="visible-signed-in">
                    <a href="/uk/pokemon-trainer-club/login">
                        <div class="avatar-icon-wrapper">
                            <img class="avatar-icon avatar-icon-mobile"
                                 src="https://assets.pokemon.com/static2/_ui/img/chrome/profile-navigation/profile-nav-avatar.png"
                                 alt="View Profile"/>
                        </div>
                    </a>
                </li>

                <li class="visible-not-signed-in">
                    <a href="/uk/pokemon-trainer-club/login">
                        <div class="avatar-icon-wrapper">
                            <img class="avatar-icon avatar-icon-mobile"
                                src="https://assets.pokemon.com/static2/_ui/img/chrome/profile-navigation/profile-nav-signup.png"
                                alt="Sign In / Sign Up"/>
                        </div>
                        <div class="sign-in-text-wrapper sign-in-text-wrapper-mobile">
                            Log In
                        </div>
                    </a>
                </li>
            </ul>
        </div>

        <ul data-analytics-label="primary-nav">

  


<li class="home">
  <a href="/uk/"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_home">
        
        
        
    </span>

    <span class="title title_home">Home</span>
  </a>



</li>



<li class="explore">
  <a href="/uk/pokedex/"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_pokeball">
        
        
        
    </span>

    <span class="title title_pokeball">Pokédex</span>
  </a>



</li>



<li class="watch">
  <a href="/uk/pokemon-video-games/"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_joystick">
        
        
        
    </span>

    <span class="title title_joystick">Video Games & Apps</span>
  </a>



</li>



<li class="play">
  <a href="/uk/pokemon-tcg/"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_cards">
        
        
        
    </span>

    <span class="title title_cards">Trading Card Game</span>
  </a>



</li>



<li class="attend">
  <a href="/uk/animation"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_pokemontv">
        
        
        
    </span>

    <span class="title title_pokemontv">Animation</span>
  </a>



</li>



<li class="trade">
  <a href="/uk/play-pokemon/"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_event">
        
        
        
    </span>

    <span class="title title_event">Play! Pokémon Events</span>
  </a>

<a href="#" class="subnav-toggle"><span class="icon"></span></a>

<ul class="subnav secondary">

    <li class="subnav-title"
        data-content-id=""
        data-content-type="Sidebar"
        data-content-variation="sidebarLeft"
        data-content-location=""
        data-content-category=""
        data-content-download="">
        <a href="#" class="subnav-toggle"><span class="icon"></span></a>
        <a href="#"><span class="title">Play! Pokémon Events</span></a>
    </li>


    
<li>
    <a href="/uk/play-pokemon/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Play! Pokémon Events</a>
    
    <a href="#" class="subnav-toggle"><span class="icon"></span></a>

<ul class="subnav tertiary">

    <li class="subnav-title"
        data-content-id=""
        data-content-type="Sidebar"
        data-content-variation="sidebarLeft"
        data-content-location=""
        data-content-category=""
        data-content-download="">
        <a href="#" class="subnav-toggle"><span class="icon"></span></a>
        <a href="#"><span class="title">Play! Pokémon Events</span></a>
    </li>


    
<li>
    <a href="/uk/play-pokemon/pokemon-events/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Play! Pokémon Events</a>
    
    <a href="#" class="subnav-toggle"><span class="icon"></span></a>

<ul class="subnav tertiary">

    <li class="subnav-title"
        data-content-id=""
        data-content-type="Sidebar"
        data-content-variation="sidebarLeft"
        data-content-location=""
        data-content-category=""
        data-content-download="">
        <a href="#" class="subnav-toggle"><span class="icon"></span></a>
        <a href="#"><span class="title">Play! Pokémon Events</span></a>
    </li>


    
<li>
    <a href="/uk/play-pokemon/pokemon-events/find-an-event/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Event Locator</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/pokemon-events/play-in-a-league/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Pokémon League</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/pokemon-events/pokemon-tournaments/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Pokémon Championship Series</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/pokemon-events/pokemon-tournaments/earn-championship-points/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Championship Points</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/leaderboards/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Championship Rating and Rankings</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/pokemon-events/pre-release-tournaments/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Prerelease Tournaments</a>
    
    
    
</li>


</ul>

    
</li>
<li>
    <a href="/uk/play-pokemon/about/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">About Play! Pokémon</a>
    
    <a href="#" class="subnav-toggle"><span class="icon"></span></a>

<ul class="subnav tertiary">

    <li class="subnav-title"
        data-content-id=""
        data-content-type="Sidebar"
        data-content-variation="sidebarLeft"
        data-content-location=""
        data-content-category=""
        data-content-download="">
        <a href="#" class="subnav-toggle"><span class="icon"></span></a>
        <a href="#"><span class="title">About Play! Pokémon</span></a>
    </li>


    
<li>
    <a href="/uk/play-pokemon/about/play-points/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Play! Points</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/about/tournaments-rules-and-resources/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Rules & Resources</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/about/tournaments-glossary/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Play! Pokémon Glossary</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/about/video-game-glossary/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Video Game Glossary</a>
    
    
    
</li>
<li>
    <a href="/uk/play-pokemon/about/parents-guide/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Parents Guide</a>
    
    
    
</li>


</ul>

    
</li>
<li>
    <a href="/uk/play-pokemon/organize/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Organize Events</a>
    
    
    
</li>


</ul>

    
</li>
<li>
    <a href="/uk/play-pokemon/leaderboards/"
       
       
       
       data-content-id=""
       data-content-type="Sidebar"
       data-content-variation="sidebarLeft"
       data-content-location=""
       data-content-category=""
       data-content-download=""
       target="_self">Play! Pokémon Leaderboards</a>
    
    
    
</li>


</ul>


</li>



<li class="game last-item">
  <a href="/uk/pokemon-news/"
     
     
     
     target="_self"
     data-content-id=""
     data-content-type="Sidebar"
     data-content-variation="sidebarLeft"
     data-content-location=""
     data-content-category=""
     data-content-download="">
    <span class="fill"></span>

    <span class="icon icon_news">
        
        
        
    </span>

    <span class="title title_news">News</span>
  </a>



</li>



    <li class="search">
        <div class="search-wrapper">
            <form id="mobile-nav-site-search-widget" action="/search/" method="GET">
                <input id="mobile-search" type="search" value="" placeholder="Search" name="q"
                       id="mobile-nav-site-search-widget-term"/>
                <span class="icon icon_search"></span>
            </form>
        </div>
    </li>
</ul>



    </div>

</nav>
<div id="user-dashboard" class="default-background">
    <div class="drawer">
        <nav class="profile-nav hidden-mobile">
            <ul class="dashboard-open">
                <li class="visible-not-signed-in sign-up">
                    <a href="https://club.pokemon.com/uk/pokemon-trainer-club/login">
                        <span class="">
                            <div class="avatar-icon-wrapper">
                                <img class="avatar-icon" src="https://assets.pokemon.com/static2/_ui/img/chrome/profile-navigation/profile-nav-signup.png"
                                     alt="Log In"/>
                            </div>
                            <div class="sign-in-text-wrapper">
                                Log In
                            </div>
                        </span>
                    </a>
                </li>

                <li class="visible-signed-in">
                    <a href="https://club.pokemon.com/uk/pokemon-trainer-club/edit-profile/">
                        <span class="">
                            <div class="avatar-icon-wrapper">
                                <img class="avatar-icon"
                                     src="https://assets.pokemon.com/static2/_ui/img/chrome/profile-navigation/profile-nav-avatar.png"
                                     alt="Profile"/>
                            </div>
                        </span>
                    </a>
                </li>

                <li class="visible-signed-in organizer-link">
                    <a href="/uk/pokemon-trainer-club/play-pokemon/events/">
                            <span class="" >
                                <div class="organizer-icon-wrapper">
                                    <img class="organizer-icon default" alt="Profile"
                                         src="https://assets.pokemon.com/static2/_ui/img/chrome/profile-navigation/profile-nav-builder.png" />
                                    <img class="organizer-icon ie9-hover" alt="Profile"
                                         src="https://assets.pokemon.com/static2/_ui/img/chrome/profile-navigation/profile-nav-builder-ie9-hover.png" />
                                    <span class="offscreen">Profile</span>
                                </div>
                            </span>
                    </a>
                </li>

                <li class="visible-signed-in sign-in" id="sidebar-logout-button">
                    <a href="/uk/pokemon-trainer-club/logout">
                        <span>Log Out</span>
                    </a>
                </li>

            </ul>
            <div class="search">
                <a class="icon icon_search" href="">
                    <span class="offscreen"></span>
                </a>
            </div>
            <div class="bottom-angle"></div>
        </nav>

        <div class="dashboard"></div>

    </div>

</div>

        <div class="container ">

<section class="mosaic section"  data-tile-template="MosaicDefault">

    <script>
        window.pokemonMosaicType = 'MosaicDefault';
    </script>


        <div class="column-8 push-1" data-tile-position="Main">

    <a href="/uk/pokemon-news/get-the-pokemon-tcg-scarlet-violet-temporal-forces-build-battle-box-early"
        
        class=""
        
    >
<div class="content-block  content-block-full content-hero ">

        <div class=content-hero-wrapper>


        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/trading-card-game/series/incrementals/2024/sv05-build-battle-box/sv05-build-battle-box-a-169-en.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/trading-card-game/series/incrementals/2024/sv05-build-battle-box/sv05-build-battle-box-a-169-en.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/trading-card-game/series/incrementals/2024/sv05-build-battle-box/sv05-build-battle-box-a-169-en.png"
                     alt="Have a Blast with the Pokémon TCG: Scarlet & Violet—Temporal Forces Build & Battle Box"/>
        </div>

                <div class="banner banner banner-lightblue">
                    <h3>Have a Blast with the Pokémon&nbsp;TCG: <em>Scarlet & Violet—Temporal Forces</em> Build & Battle Box</h3>
                    <p>Experience the power of Ancient and Future Pokémon before this expansion officially launches on March 22, 2024.</p>
            </div>


        </div>

</div>
    </a>


    <a href="/uk/pokemon-news/an-early-look-at-cards-from-the-pokemon-tcg-scarlet-violet-temporal-forces-expansion"
        
        class=""
        
    >
<div class="content-block  content-block-half-first ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/trading-card-game/_tiles/sv/sv05/preview-cards/sv05-preview-cards-1-169-en.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/trading-card-game/_tiles/sv/sv05/preview-cards/sv05-preview-cards-1-169-en.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/trading-card-game/_tiles/sv/sv05/preview-cards/sv05-preview-cards-1-169-en.png"
                     alt="New Cards in Temporal Forces"/>
        </div>

                <div class="banner banner banner-lightpurple">
                    <h3>New Cards in <em>Temporal Forces</em></h3>
            </div>



</div>
    </a>


    <a href="/uk/strategy/catch-legendary-pokemon-and-paradox-pokemon-in-the-indigo-disk"
        
        class=""
        
    >
<div class="content-block  content-block-half ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/scarlet-violet/the-indigo-disk/elusive-pokemon/scarlet-violet-169-en.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/scarlet-violet/the-indigo-disk/elusive-pokemon/scarlet-violet-169-en.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/scarlet-violet/the-indigo-disk/elusive-pokemon/scarlet-violet-169-en.png"
                     alt="Catch Elusive Pokémon in The Indigo Disk"/>
        </div>

                <div class="banner banner banner-blue">
                    <h3>Catch Elusive Pokémon in <em>The Indigo Disk</em></h3>
            </div>



</div>
    </a>

        </div>

        <div class="column-4 push-9" data-tile-position="Right_">


    <a href="/uk/pokemon-news/updates-from-the-pokemon-day-2024-pokemon-presents"
        
        class=""
        
    >
<div class="content-block  content-block-full ">


        <div class="banner banner-right banner-gray">

        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-presents/02272024/pokemon-presents-34.jpg"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-presents/02272024/pokemon-presents-34.jpg"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-presents/02272024/pokemon-presents-34.jpg"
                     alt="Pokémon Presents Recap"/>
        </div>

                <div class="banner-wrapper">
                    <h3>Pokémon Presents Recap</h3>
            </div>

        </div>


</div>
    </a>


    <a href="/uk/pokemon-news/encounter-dedenne-during-pokemon-sleeps-electric-type-week"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-sleep/2024/03042024/pokemon-sleep-169.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-sleep/2024/03042024/pokemon-sleep-169.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-sleep/2024/03042024/pokemon-sleep-169.png"
                     alt="Add Some Spark to Your Teams in Pokémon Sleep"/>
        </div>

                <div class="banner banner banner-green">
                    <h3>Add Some Spark to Your Teams in Pokémon Sleep</h3>
            </div>



</div>
    </a>


    <a href="/uk/strategy/pokemon-go-world-of-wonders-season-trainer-battle-updates"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/go/battle-league/2024/world-of-wonders/pokemon-go-169.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/go/battle-league/2024/world-of-wonders/pokemon-go-169.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/go/battle-league/2024/world-of-wonders/pokemon-go-169.png"
                     alt="Prepare for Wondrous Battles in Pokémon GO"/>
        </div>

                <div class="banner banner banner-yellow">
                    <h3>Prepare for Wondrous Battles in Pokémon&nbsp;GO</h3>
            </div>



</div>
    </a>


        </div>

        <div class="loader"></div>

</section>


<noscript>

                <div>
                    <a href="/uk/pokemon-news/get-the-pokemon-tcg-scarlet-violet-temporal-forces-build-battle-box-early">
                            <h3>Have a Blast with the Pokémon&nbsp;TCG: <em>Scarlet & Violet—Temporal Forces</em> Build & Battle Box</h3>
                            <p>Experience the power of Ancient and Future Pokémon before this expansion officially launches on March 22, 2024.</p>
                            <img src="/static-assets/content-assets/cms2/img/trading-card-game/series/incrementals/2024/sv05-build-battle-box/sv05-build-battle-box-a-169-en.png" alt="Have a Blast with the Pokémon TCG: Scarlet & Violet—Temporal Forces Build & Battle Box" />
                    </a>
                </div>


                <div>
                    <a href="/uk/pokemon-news/updates-from-the-pokemon-day-2024-pokemon-presents">
                            <h3>Pokémon Presents Recap</h3>
                            <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-presents/02272024/pokemon-presents-34.jpg" alt="Pokémon Presents Recap" />
                    </a>
                </div>


                <div>
                    <a href="/uk/pokemon-news/encounter-dedenne-during-pokemon-sleeps-electric-type-week">
                            <h3>Add Some Spark to Your Teams in Pokémon Sleep</h3>
                            <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-sleep/2024/03042024/pokemon-sleep-169.png" alt="Add Some Spark to Your Teams in Pokémon Sleep" />
                    </a>
                </div>


                <div>
                    <a href="/uk/pokemon-news/an-early-look-at-cards-from-the-pokemon-tcg-scarlet-violet-temporal-forces-expansion">
                            <h3>New Cards in <em>Temporal Forces</em></h3>
                            <img src="/static-assets/content-assets/cms2/img/trading-card-game/_tiles/sv/sv05/preview-cards/sv05-preview-cards-1-169-en.png" alt="New Cards in Temporal Forces" />
                    </a>
                </div>


                <div>
                    <a href="/uk/strategy/catch-legendary-pokemon-and-paradox-pokemon-in-the-indigo-disk">
                            <h3>Catch Elusive Pokémon in <em>The Indigo Disk</em></h3>
                            <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/scarlet-violet/the-indigo-disk/elusive-pokemon/scarlet-violet-169-en.png" alt="Catch Elusive Pokémon in The Indigo Disk" />
                    </a>
                </div>


                <div>
                    <a href="/uk/strategy/pokemon-go-world-of-wonders-season-trainer-battle-updates">
                            <h3>Prepare for Wondrous Battles in Pokémon&nbsp;GO</h3>
                            <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/strategy/go/battle-league/2024/world-of-wonders/pokemon-go-169.png" alt="Prepare for Wondrous Battles in Pokémon GO" />
                    </a>
                </div>

</noscript>



<section id="pokemon-character-slider" class="slider-widget preload-images">

    <div class="slider-title">
        <div class="column-12 push-1">
            <h3 class="pokemon-character-slider-title">
                <span class="notch-left-top-outer"></span>
                <span class="icon icon_pokeball"></span>
                    Featured Pokémon
            </h3>
        </div>
    </div>

    <div class="slider-wrapper">
        <ul class="slider">
                <li data-analytics-label="Indeedee | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">876</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/876.png"
                    class="pokemon-character preload"
                    alt="Indeedee" >
                    <div class="mini-profile">
                        <h5>Indeedee
                            <span class="pokedex">876</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-psychic">
                                    Psychic
                                </span>
                                <span class="type-label background-color-normal">
                                    Normal
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Inner Focus</span>
                                    /
                                    <span class="ability-label">Synchronize</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/indeedee" class="block-link" title="Indeedee" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Indeedee Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Carvanha | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">318</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/318.png"
                    class="pokemon-character preload"
                    alt="Carvanha" >
                    <div class="mini-profile">
                        <h5>Carvanha
                            <span class="pokedex">318</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-water">
                                    Water
                                </span>
                                <span class="type-label background-color-dark">
                                    Dark
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Rough Skin</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/carvanha" class="block-link" title="Carvanha" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Carvanha Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Dartrix | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">723</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/723.png"
                    class="pokemon-character preload"
                    alt="Dartrix" >
                    <div class="mini-profile">
                        <h5>Dartrix
                            <span class="pokedex">723</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-grass">
                                    Grass
                                </span>
                                <span class="type-label background-color-flying">
                                    Flying
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Overgrow</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/dartrix" class="block-link" title="Dartrix" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Dartrix Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Wigglytuff | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">40</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/040.png"
                    class="pokemon-character preload"
                    alt="Wigglytuff" >
                    <div class="mini-profile">
                        <h5>Wigglytuff
                            <span class="pokedex">40</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-normal">
                                    Normal
                                </span>
                                <span class="type-label background-color-fairy">
                                    Fairy
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Competitive</span>
                                    /
                                    <span class="ability-label">Cute Charm</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/wigglytuff" class="block-link" title="Wigglytuff" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Wigglytuff Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Boltund | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">836</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/836.png"
                    class="pokemon-character preload"
                    alt="Boltund" >
                    <div class="mini-profile">
                        <h5>Boltund
                            <span class="pokedex">836</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-electric">
                                    Electric
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Strong Jaw</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/boltund" class="block-link" title="Boltund" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Boltund Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Tapu Lele | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">786</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/786.png"
                    class="pokemon-character preload"
                    alt="Tapu Lele" >
                    <div class="mini-profile">
                        <h5>Tapu Lele
                            <span class="pokedex">786</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-psychic">
                                    Psychic
                                </span>
                                <span class="type-label background-color-fairy">
                                    Fairy
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Psychic Surge</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/tapu-lele" class="block-link" title="Tapu Lele" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Tapu Lele Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Gothitelle | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">576</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/576.png"
                    class="pokemon-character preload"
                    alt="Gothitelle" >
                    <div class="mini-profile">
                        <h5>Gothitelle
                            <span class="pokedex">576</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-psychic">
                                    Psychic
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Competitive</span>
                                    /
                                    <span class="ability-label">Frisk</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/gothitelle" class="block-link" title="Gothitelle" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Gothitelle Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Kadabra | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">64</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/064.png"
                    class="pokemon-character preload"
                    alt="Kadabra" >
                    <div class="mini-profile">
                        <h5>Kadabra
                            <span class="pokedex">64</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-psychic">
                                    Psychic
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Inner Focus</span>
                                    /
                                    <span class="ability-label">Synchronize</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/kadabra" class="block-link" title="Kadabra" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Kadabra Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Skitty | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">300</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/300.png"
                    class="pokemon-character preload"
                    alt="Skitty" >
                    <div class="mini-profile">
                        <h5>Skitty
                            <span class="pokedex">300</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-normal">
                                    Normal
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Cute Charm</span>
                                    /
                                    <span class="ability-label">Normalize</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/skitty" class="block-link" title="Skitty" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Skitty Profile</span>
                    </a>
                </li>
                <li data-analytics-label="Barbaracle | " 
                    data-content-id="featured-item"
                    data-content-type="Slider"
                    data-content-variation="slideCenter"
                    data-content-location=""
                    data-content-category="Featured Pokemon"
                    data-content-download="">
                    <div class="pokedex-bg">689</div>
                    <img data-preload-src="/static-assets/content-assets/cms2/img/pokedex/full/689.png"
                    class="pokemon-character preload"
                    alt="Barbaracle" >
                    <div class="mini-profile">
                        <h5>Barbaracle
                            <span class="pokedex">689</span>
                        </h5>
                        <dl>
                            <dt>Type</dt>
                            <dd class="types">
                                <span class="type-label background-color-rock">
                                    Rock
                                </span>
                                <span class="type-label background-color-water">
                                    Water
                                </span>
                            </dd>
                            <dt>Abilities</dt>
                            <dd class="abilities">
                                    <span class="ability-label">Sniper</span>
                                    /
                                    <span class="ability-label">Tough Claws</span>
                                    
                            </dd>
                        </dl>
                        <span class="notch-bottom-center-small"></span>
                    </div>

                    <a href="/uk/pokedex/barbaracle" class="block-link" title="Barbaracle" style="background-color: #fff; opacity: 0;">
                        <span class="offscreen">Barbaracle Profile</span>
                    </a>
                </li>
        </ul>
    </div>

    <div class="slider-more-button">
        <div class="column-12 push-1">
            <div class="content-block content-block-full">
                <a class="button button-black right"
                       href="/uk/pokedex/"
                >
                        Explore More Pokémon
                </a>
            </div>
        </div>
    </div>

</section>


<noscript>
<div>
    <a href="/uk/pokedex/indeedee">
        <h5>Indeedee</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/876.png"
             alt="Indeedee" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/carvanha">
        <h5>Carvanha</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/318.png"
             alt="Carvanha" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/dartrix">
        <h5>Dartrix</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/723.png"
             alt="Dartrix" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/wigglytuff">
        <h5>Wigglytuff</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/040.png"
             alt="Wigglytuff" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/boltund">
        <h5>Boltund</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/836.png"
             alt="Boltund" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/tapu-lele">
        <h5>Tapu Lele</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/786.png"
             alt="Tapu Lele" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/gothitelle">
        <h5>Gothitelle</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/576.png"
             alt="Gothitelle" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/kadabra">
        <h5>Kadabra</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/064.png"
             alt="Kadabra" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/skitty">
        <h5>Skitty</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/300.png"
             alt="Skitty" />
    </a>
</div>
<div>
    <a href="/uk/pokedex/barbaracle">
        <h5>Barbaracle</h5>
        <img src="/static-assets/content-assets/cms2/img/pokedex/full/689.png"
             alt="Barbaracle" />
    </a>
</div>
</noscript>



<section class="mosaic section" data-tile-template="MosaicD">

    <script>
                window.pokemonMosaicType = 'MosaicD';
    </script>

    <div class="column-4 push-1 staggered-1" data-tile-position="Left_">

            <div class="content-block content-block-full visible-mobile">
                <h2 class="section-title">What's New This Week</h2>
            </div>



    <a href="https://tcgpocket.pokemon.com/en-gb/"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/tcg-pocket/announce/tcg-pocket-169-en.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/tcg-pocket/announce/tcg-pocket-169-en.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/tcg-pocket/announce/tcg-pocket-169-en.png"
                     alt="Discover a New Way to Experience the Pokémon TCG"/>
        </div>

                <div class="banner banner banner-gray">
                    <h3>Discover a New Way to Experience the Pokémon&nbsp;TCG</h3>
                    <p>Collect digital trading cards in Pokémon Trading Card Game Pocket, coming in 2024 for iOS and Android devices.</p>
            </div>



</div>
    </a>

    <a href="/uk/pokemon-news/scout-geeta-glimmora-and-more-during-the-pokemon-masters-ex-4-5-year-celebration"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-masters/2024/02272024/pokemon-masters-ex-169.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-masters/2024/02272024/pokemon-masters-ex-169.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-masters/2024/02272024/pokemon-masters-ex-169.png"
                     alt="Team Up with New Sync Pairs and Snap Some Pics during This Special Celebration"/>
        </div>

                <div class="banner banner banner-blue">
                    <h3>Team Up with New Sync Pairs and Snap Some Pics during This Special Celebration</h3>
                    <p>The Pokémon Masters&nbsp;EX 4.5 Year Celebration showcases new sync pairs, bonuses, and a brand-new photo creator feature.</p>
            </div>



</div>
    </a>

    </div>

    <div class="column-4 push-5" data-tile-position="Middle_">


    <a href="https://legends.pokemon.com/en-gb/"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-legends-z-a/announce/pokemon-legends-z-a-169-en.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-legends-z-a/announce/pokemon-legends-z-a-169-en.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-legends-z-a/announce/pokemon-legends-z-a-169-en.png"
                     alt="A New Legend Is about to Begin"/>
        </div>

                <div class="banner banner banner-green">
                    <h3>A New Legend Is about to Begin</h3>
                    <p><em>Pokémon Legends: Z&#8209;A</em>, an upcoming adventure set within Lumiose City, will launch on Nintendo Switch in 2025.</p>
            </div>



</div>
    </a>

            <div class="content-block content-block-full hidden-mobile">
                <h2 class="section-title">What's New This Week</h2>
            </div>


    <a href="/uk/pokemon-news/challenge-venusaur-charizard-and-blastoise-in-tera-raid-battles"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-scarlet-violet/events/2024/02272024/scarlet-violet-169-en.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-scarlet-violet/events/2024/02272024/scarlet-violet-169-en.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-scarlet-violet/events/2024/02272024/scarlet-violet-169-en.png"
                     alt="Kick It Back to 1996 with Venusaur, Charizard, and Blastoise in Tera Raid Battles"/>
        </div>

                <div class="banner banner banner-orange">
                    <h3>Kick It Back to 1996 with Venusaur, Charizard, and Blastoise in Tera Raid Battles</h3>
                    <p>Celebrate Pokémon Day by adding these iconic Pokémon to your team as they appear in 7-star Tera Raid battles in the <em>Pokémon Scarlet</em> and <em>Pokémon Violet</em> games.</p>
            </div>



</div>
    </a>
    </div>

    <div class="column-4 push-9 staggered-2" data-tile-position="Right_">


    <a href="/uk/pokemon-news/charcadet-makes-its-pokemon-go-debut-during-pokemon-horizons-the-series-celebration-event"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-go/2024/02272024/pokemon-go-169.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-go/2024/02272024/pokemon-go-169.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-go/2024/02272024/pokemon-go-169.png"
                     alt="New Horizons in Pokémon GO"/>
        </div>

                <div class="banner banner banner-black">
                    <h3>New Horizons in Pokémon&nbsp;GO</h3>
                    <p>Celebrate <em>Pokémon Horizons: The Series</em> with the debut of Charcadet and Pikachu wearing Cap’s hat.</p>
            </div>



</div>
    </a>


    <a href="/uk/pokemon-news/celebrate-pokemon-day-with-miraidon-in-pokemon-unite"
        
        class=""
        
    >
<div class="content-block  content-block-full ">



        <div class="tile-image-wrapper">
                <img src="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-unite/2024/02272024/pokemon-unite-169.png"
                     class="breakpoint rating-image"
                     data-maxwidth720px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-unite/2024/02272024/pokemon-unite-169.png"
                     data-minwidth721px="/static-assets/content-assets/cms2/img/video-games/_tiles/pokemon-unite/2024/02272024/pokemon-unite-169.png"
                     alt="Miraidon Electrifies Pokémon UNITE this Pokémon Day"/>
        </div>

                <div class="banner banner banner-yellow">
                    <h3>Miraidon Electrifies Pokémon UNITE this Pokémon Day</h3>
                    <p>Celebrate Pokémon Day in Pokémon UNITE by completing missions to get Miraidon’s Unite license during the Miraidon’s Sandwich Challenge event.</p>
            </div>



</div>
    </a>

            <a href="/uk/pokemon-news" data-analytics-label="#need-analytics-label">
                <div class="content-block content-block-full">
                    <div class="color-block color-block-orange">
                        <h2>View All News</h2>
                    </div>
                        <div class="banner banner-lightblue dog-ear-br">
                            <p>Keep up with all the latest developments!</p>
                        </div>
                </div>
            </a>
    </div>

    <div class="loader"></div>

</section>


        </div>


  <div id="back-to-top" class="visible-mobile">
    <span class="offscreen">Back to Top</span>
  </div>

  <div class="footer-divider">
    <span class="footer-notch"></span>
  </div>

  <footer class="global-footer">

<div class="global-footer-email">
    <p class="footer-email-title">Sign up for Pok&eacute;mon&nbsp;emails!</p>
    <div class="footer-email-container disable-custom-select-menu">
        <div class="footer-email-form">
            <input type="email" name="email-signup-email-text" id="email-signup-email-text" placeholder="Email" class="footer-white-box" required />
            <div class="region_dob_wrap">
                <select id="email-signup-regions" class="footer-white-box footer-region-select" required>
                </select>
                <input type="text" class="footer-email-input footer-white-box" title="Birthday" id="email-signup-dob" placeholder="Birthday" />
            </div>
        </div>
        <div class="footer-email-notification-options">
            <p class="email_msg">I’d like to receive emails&nbsp;about:</p>
            <div class="footer-email-checkbox-wrapper-1">
                <input type="checkbox" id="email-signup-vg-apps" name="email-signup-vg-apps" value="pokemon_news" class="footer-email-checkbox">
                <label for="email-signup-vg-apps"> Pokémon video games, apps, and&nbsp;more</label>
            </div>
            <div class="footer-email-checkbox-wrapper-1" id="email-signup-pc-container">
                <input type="checkbox" id="email-signup-pc" name="email-signup-pc" value="pcenter" class="footer-email-checkbox">
                <label for="email-signup-pc"> Pokémon Center (our official online&nbsp;shop)</label>
            </div>
            <div class="footer-email-checkbox-wrapper-1">
                <input type="checkbox" id="email-signup-terms" name="email-signup-terms" value="terms" class="footer-email-checkbox">
                <label for="email-signup-terms">
                    I accept the Pokemon.com <a class="footer-email-link" href="https://www.pokemon.com/uk/terms-of-use">Terms&nbsp;of&nbsp;Use</a> and <a class="footer-email-link" href="https://www.pokemon.com/uk/privacy-notice">Privacy&nbsp;Policy</a>
                </label>
            </div>
        </div>
    </div>
    <input type="submit" name="submit_button" value="SIGN UP" class="footer-email-sumbit" id="email-signup-submit-button"/>
</div>    <div class="content-wrapper match-height-tablet">


<div class="global-footer-links match">
  <h2><span class="offscreen">The Pok&eacute;mon Company</span></h2>
  <ul>
        <li>
          <a href="/uk/pokemon-news/" rel="" title="">
            News
          </a>
        </li>

      <li>
        <a href="/uk/parents-guide/" rel="" title="">
         Parents Guide
        </a>
      </li>

      <li>
        <a href="/uk/customer-service/" rel="" title="">
          Customer Service
        </a>
      </li>

      <li>
        <a href="https://corporate.pokemon.com/en-gb/" rel="" title="" id="about-our-company-link">
          About Our Company
        </a>
      </li>

        <li>
          <a id="careers-link" href="https://boards.greenhouse.io/pokemoncareers" class="exit-link"
            target="_blank"
            rel="https://boards.greenhouse.io/pokemoncareers"
            title="External: https://boards.greenhouse.io/pokemoncareers">
            Careers
          </a>
        </li>

    <li>
      <a href="/uk/country-region/" rel="" title="">
        Select a Country/Region
        <i class="icon-uk"></i>
      </a>
    </li>

    <li>
      <a id="press-link" href="https://pokemon.gamespress.com/en-gb" class="exit-link"
        target="_blank"
        rel="https://pokemon.gamespress.com/en-gb"
        title="External: https://pokemon.gamespress.com/en-gb">
        Press Site
      </a>
    </li>

  </ul>
</div>

<div class="global-footer-social match">

    <div class="footer-social-wrapper">
        <div class="find-us">
            <div class="find-us-box">

                <a href="https://www.facebook.com/PokemonUKGB" class="facebook exit-link" target="_blank"
                   title="External: https://www.facebook.com/PokemonUKGB">
                    <span class="offscreen">Facebook</span>
                </a>

                <a href="https://www.youtube.com/user/Pokemon" class="youtube exit-link" target="_blank"
                   title="External: https://www.youtube.com/user/Pokemon">
                    <span class="offscreen">Youtube</span>
                </a>

                <a href="https://www.twitter.com/PokemonNewsUK" class="twitter exit-link" target="_blank"
                   title="External: https://www.twitter.com/PokemonNewsUK">
                    <span class="offscreen">Twitter</span>
                </a>

                    <a href="https://www.instagram.com/PokemonNewsUK" class="instagram exit-link" target="_blank"
                       title="External: https://www.instagram.com/PokemonNewsUK">
                        <span class="offscreen">Instagram</span>
                    </a>


            </div>
        </div>

    </div>

</div>

<div class="global-footer-legal match">

  <div class="footer-legal-wrapper">

    <div id="footer--privacy">
        <a
            title="External: https://caru.bbbprograms.org/seal/Confirmation/1596150491"
                href="/uk/privacy-notice/"
            >
        </a>

      <ul>

          <li>
            <a href="/uk/terms-of-use/">Terms of Use</a>
          </li>

          <li>
            <a href="/uk/privacy-notice/">Privacy Notice</a>
          </li>

          <li>
            <a id="cookieLink" href="/uk/cookie-page/">Cookie Page</a>
          </li>

          <li>
            <a href="/uk/legal/">Legal Info</a>
          </li>

            <li>
              <a id="securityLink" href="/uk/vulnerability-disclosure-program/">Security</a>
            </li>

        </ul>
    </div>


    <span>©2023 Pokémon. ©1995 - 2023 Nintendo/Creatures Inc./GAME FREAK inc. TM, ®Nintendo.</span>

  </div>

</div>

    </div>
  </footer>


  


<div id="modal" class="popup">
	<div class="externalLink">
    <h6>

      You are about to leave a site operated by The Pokémon Company International, Inc.

    </h6>
		<p>

The Pokémon Company International is not responsible for the content of any linked website that is not operated by The Pokémon Company International. Please note that these websites' privacy policies and security practices may differ from The Pokémon Company International's standards.

    </p>
		<div class="buttons-wrapper">
			<a href="#" class="button button-green arrow-right continueBtn">

        Continue

      </a>
			<a href="#" class="button button-darkgray arrow-left closeBtn">

        Cancel

      </a>
		</div>
	</div>
</div>

<div id="pokemon-center-modal" class="popup">
	<div class="externalLink centerLink">
    <h6>
      Click Continue to visit PokemonCenter.com, our official online shop.
    </h6>
    <h6>
      The privacy and security policies differ.
    </h6>
		<div class="buttons-wrapper">
			<a href="#" class="button button-green arrow-right continueBtn">

        Continue

      </a>
			<a href="#" class="button button-darkgray arrow-left closeBtn" target="_blank">

        Cancel

      </a>
		</div>
	</div>
</div>

<div id="site-search-modal" class="popup">

	<form id="site-search-widget" class="form-analytics" name="site-search-modal">
		<span class="search"><input type="search" placeholder="Search" name="search" id="site-search-widget-term" autocomplete="off" /></span>
		<span class="submit icon icon_search"><input type="submit" value="" id="site-search-widget-submit"/></span>
        <div id="modal-search-results"></div>
	</form>
</div>

<div id='report-screen-name-success-modal' class='popup'>
  <h6>Report Inappropriate Screen Name</h6>

  <div class='modalBox'>
    <img src="https://assets.pokemon.com/static2/_ui/img/chrome/external_link_bumper.png" alt="" class="hidden-mobile" />

    <p>
    Pokemon.com administrators have been notified and will review the screen name for compliance with the Terms of Use.
    </p>

    <div class='buttons-wrapper'>
      <a href='#' class='button button-orange closeBtn'>
        Close
      </a>
    </div>
  </div>
</div>

<div id='report-screen-name-failure-modal' class='popup'>
  <h6>Report Inappropriate Screen Name</h6>

  <div class='modalBox'>
    <img src="https://assets.pokemon.com/static2/_ui/img/chrome/external_link_bumper.png" alt="" class="hidden-mobile" />

    <p>
    Your request could not be completed. Please try again. If the problem persists, please contact Customer Support.
    </p>

    <div class='buttons-wrapper'>
      <a href='#' class='button button-orange closeBtn'>
        Close
      </a>
    </div>
  </div>
</div>

    <div id="email-signup-success" class="email-modal-content popup" tabindex="0">
        <div class="email-modal-close-icon-container">
            <a tabindex="0" class="icon icon_multiply email-modal-close-icon closeBtn"></a>
        </div>
        <div class="email-modal-body modalBox">
            <span class="icon icon_check email-modal-big-icon" style="color: green;"></span>
            <p class="email-modal-emphasis-text">You have successfully signed up for Pokémon&nbsp;emails!</p>
            <p>We'll send you a few emails every week.</p>
            <p>Unsubscribe at any time using the link in your email's&nbsp;footer.</p>
        </div>
    </div>

    <div id="email-signup-failure" class="email-modal-content popup" tabindex="0">
        <div class="email-modal-close-icon-container">
            <a tabindex="0" class="icon icon_multiply email-modal-close-icon closeBtn"></a>
        </div>
        <div class="email-modal-body modalBox">
            <p class="email-modal-emphasis-text">We're sorry, but we can't process your request.</p>
            <p>We can't sign you up for emails right&nbsp;now.</p>
            <p>You can visit <a href="https://www.pokemon.com/uk/">pokemon.com</a> for the latest Pokémon news or contact Customer&nbsp;Support&nbsp;<a href="https://support.pokemon.com/hc/en-us/articles/20573695697428">here</a>.</p>
        </div>
    </div>
<div id='popupScreen' class="popupScreen"></div>


  
    
<div id="video-modal" class="popup">
<span class="watch-token-info"><span class="token_icon"></span><p class="token_verbal">You've been awarded <span class="token_amount">0</span> Token(s) for watching Pokémon TV!</p></span>
    <div class="video-modal-wrapper">

        <header class="video-header">
            <h4 id="episodeInfo">

            </h4>
            <!-- HEADLINE -->
            <h1 id="episodeTitle"></h1>
        </header>

        <div class="video-container">
        </div>

        <p class="legal" style="padding-top: 10px"></p>

        <p class="video-summary">

        </p>

        

        <a href="#" class="closeBtn button button-orange no-arrow right"><i class="icon icon_multiply"></i> Close</a>

    </div>

</div>


<script type="text/javascript">
    // define waitSeconds above require script tag
    // to override the default, until main.js loads
    window.requirejs = {
        waitSeconds: 30 // when loaded, main.js also sets waitSeconds to 30
    };
</script>
<script data-main="https://assets.pokemon.com/static2/_ui/js/home.js"
        src="https://assets.pokemon.com/static2/_ui/js/vendor/require.js"></script>

<script type="text/javascript">
if (typeof _satellite !== "undefined") {
  _satellite.pageBottom();
}
</script>

	</body>
</html>
