/*Spritesheet*/

.arrow-upvote,
.arrow-upvoted,
.arrow-downvote,
.arrow-downvoted {
    background: url(https://i.imgur.com/jAs7MFs.png);
    width: 16px;
    height: 16px;
}
    .arrow-upvote    { background-position:   0   -12px; }
    .arrow-upvoted   { background-position: -16px -12px; }
    .arrow-downvote  { background-position:   0   -28px; }
    .arrow-downvoted { background-position: -16px -28px; }

.comment .arrow-upvote,
.comment .arrow-upvoted,
.comment .arrow-downvote,
.comment .arrow-downvoted {
    background: url(https://i.imgur.com/jAs7MFs.png);
    width: 12px;
    height: 12px;
}
    .comment .arrow-upvote    { background-position: -32px -12px; }
    .comment .arrow-upvoted   { background-position: -44px -12px; }
    .comment .arrow-downvote  { background-position: -32px -24px; }
    .comment .arrow-downvoted { background-position: -44px -24px; }

body {
    font-family: verdana, arial, helvetica, sans-serif;
    background-color: white;
    z-index: 1;
    min-height: 100%;
}
.form-control {
    border: 1px solid gray;
    font-size: 13px;
    font-family: verdana;
    box-sizing: border-box;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    padding: 6px;
    padding-right: 25px;
    padding-left: 9px;
    vertical-align: middle;
}
.form-horizontal {
    background-color: #f6e69f;
    border: 1px solid #ffa500;
    font-size: small;
    padding: 5px 10px;
}

.btn-whoaverse.contribute {
    background: white;
    background-image: url(https://i.imgur.com/SwaHz4K.png);
    color: #369;
    border: 1px solid #c4dbf1;
}
.btn-whoaverse.contribute:hover {
    background: white;
    background-image: url(https://i.imgur.com/wuTYUNb.png);
    color: #369;
    border: 1px solid #75B4F0;
}
.btn-whoaverse-paging {
    background: url(https://i.imgur.com/maXtPzS.png);
    border: 1px solid #444;
    color: white;
}
.btn-whoaverse-paging:hover {
    background: url(https://i.imgur.com/maXtPzS.png);
    border: 1px solid #444;
    color: white;
}
.btn-unsub {
    background: url(https://i.imgur.com/mcExZP5.png);
}
.btn-unsub:hover {
    background: url(https://i.imgur.com/mcExZP5.png);
}
#container,
#header-banner {
    max-width: 100%;
}
/*Misc Styling*/

.score.likes {
    color: #FF8B60 !important
}
.score.dislikes {
    color: #9494FF !important
}
.scorebar-likes {
    background: #FF8B60
}
.scorebar-dislikes {
    background: #9494FF
}
.rss-icon {
    display: none
}
a:visited {
    color: #551a8b
}
/*Banner Image*/

#header {
    background-image: url(https://i.imgtc.com/LxLaxTq.png);
    height: 201px !important;
    width: 1900px !important;
}

/*Subscriptions Bar*/

.sr-list {
    background-color: #f0f0f0;
    white-space: nowrap;
    border-bottom: 1px solid gray;
    font-size: 80%;
    height: 18px;
    line-height: 18px;
}
.sr-list li a {
    color: black;
    text-transform: uppercase;
}
#sr-more-link {
    background-color: #f0f0f0;
    white-space: nowrap;
    text-transform: uppercase;
    border-bottom: 1px solid gray;
    font-size: 90%;
    height: 18px;
    line-height: 18px;
}
.drop-arrow {
    display: none;
}
/*Header*/

#header-banner {
    margin-top: -6px;
    border-bottom: 1px solid #5f99cf;
    background-color: #cee3f8;
}
.tabmenu {
    position: relative;
    top: 16.5px;
}
.tabmenu li a {
    color: #369!important;
    font-weight: bold;
    border: 1px solid #5f99cf!important;
    border-bottom: 0px;
    background: white!important;
    color: #369;
    font-weight: bold;
    border: 0px!important;
    border-bottom: 0px;
    border-radius: 0px!important;
}
.tabmenu li.selected a {
    color: orangered!important;
    border: 1px solid #5f99cf!important;
    border-bottom: 1px solid white!important;
}
.tabmenu li {
    background: white;
}
.pagename a {
    position: relative;
    top: 19px;
    color: black;
}
.pagename a:hover {
    color: black;
    text-decoration: underline
}
.logged-in,
.logged-out {
    position: relative;
    top: 14px;
    background: rgb(239, 247, 255);
    border: 0px
}
/*Sidebar*/

.submissioninfo {
    border: 1px solid #5f99cf;
    background-color: #EFF7FF;
    font-family: arial, helvetica, sans-serif;
    color: black;
    padding-left: 6px
}
.alert-h2 {
    color: black
}
/*Comments*/

.author.submitter {
    background: blue;
    color: white !important
}
a.submitter {
    color: blue
}
.tagline .post_upvotes {
    color: #FF8B60
}
.titlebox h1 a:hover {
    color: black;
    text-decoration: underline
}
.titlebox .bottom {
    border-top: 1px solid black
}
.alert-h1 {
    color: gray
}
.sidecontentbox .content {
    border: 1px solid gray
}
/*Sign-in*/

#loginForm .form-horizontal {
    background: white;
    border: 0px
}
.modal-title {
    color: #4270a2
}
.modal-header {
    background: white;
    border: 0px
}
#loginForm .form-control {
    width: 340px;
    border-top: 1px grey
}
.modal-body .btn-whoaverse {
    background: #4f86b5;
    border-bottom: 2px solid #4270a2;
    color: #ffffff;
}

/* EDIT MODERATOR BOX */

.side .helplink + .title h1 { display: none; }
.side .helplink + .title::before { 
    content: 'THOUGHT POLICE';
    display: block;
    font-size: 120%;
    font-weight: bold;
    color:      #967aff;
    text-transform: uppercase;
}

/*Downvote message*/
        .arrow-downvote:after{
           display:block;
           visibility:hidden;
           position:absolute;
           z-index:1000;
           margin-top:-6px;
           margin-left:32px;
           padding:12px;
           background-color:rgba(79,77,192,0.0);
           border:none;
           border-radius:2px;
           color:rgba(255,255,255,0);
           content:"This hurts my fee-fees.";
           text-align:center;
           letter-spacing:1px;
           font-weight:400;
           font-size:13px;
           transition:all .25s ease;
           pointer-events:none
        }

        .arrow-downvote:hover:after{
           visibility:visible;
           background-color:rgba(24,24,24,0.9);
           color:#FFF;
           margin-left:48px
        }

/*Upvote message*/
        .arrow-upvote:after{
           display:block;
           visibility:hidden;
           position:absolute;
           z-index:1000;
           margin-top:-6px;
           margin-left:32px;
           padding:12px;
           background-color:rgba(79,77,192,0.0);
           border:none;
           border-radius:2px;
           color:rgba(255,255,255,0);
           content:"Toppest KEK, Gentlesir or Madam";
           text-align:center;
           letter-spacing:1px;
           font-weight:400;
           font-size:13px;
           transition:all .25s ease;
           pointer-events:none
        }

        .arrow-upvote:hover:after{
           visibility:visible;
           background-color:rgba(24,24,24,0.9);
           color:#FFF;
           margin-left:48px
        }
      
.content textarea { background: url(https://i.imgtc.com/WoIMtuC.png) center center no-repeat; 
  border: 1px solid #888; 
}

/*Mod Flairs*/

a[href$="/u/The_Penis_Wizard"]:after { content: "Is a fucking bitch";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/HomerSimpson"]:after { content: "Doesn't even like The Simpsons";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/Duress56"]:after { content: "Arrested for black market memes";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/Achtung_Shitlord"]:after { content: "Was killer by Tumblr";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/leelem0n"]:after { content: "Taller than claimed";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/shmuklidooha"]:after { content: "Can't think of a pronounceable username";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/R_Guilliman"]:after { content: "Thinks space is real";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/Speshul_Sn0wflake"]:after { content: "Just a regular snowflake";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/Carsandsarcasm"]:after { content: "Drives an electric car";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

/*User Flairs*/

a[href$="/u/love_rape"]:after,
a[href$="/u/imaterriblelurker"]:after,
a[href$="/u/TattooedWife"]:after,
a[href$="/u/MeowsephStalin"]:after,
a[href$="/u/shitlordcaligula"]:after,
a[href$="/u/ButterBeater9000"]:after,
a[href$="/u/L0RD-BEETUS"]:after,
a[href$="/u/shikepike"]:after,
a[href$="/u/Paramedic"]:after,
a[href$="/u/martianspider"]:after,
a[href$="/u/ranch-othelioma"]:after,
a[href$="/u/Fragnostus"]:after,
a[href$="/u/GuntPunt"]:after,
a[href$="/u/hate_the_avg"]:after,
a[href$="/u/Uglyhatemachine86"]:after,
a[href$="/u/drivesaconvertible"]:after,
a[href$="/u/flintlockwoood"]:after,
a[href$="/u/SupaDupaFUPA"]:after,
a[href$="/u/Skinnify"]:after,
a[href$="/u/BarrelchestBuffpunch"]:after,
a[href$="/u/coco86"]:after,
a[href$="/u/performance"]:after,
a[href$="/u/3l3m3nT"]:after,
a[href$="/u/Skinnyman"]:after,
a[href$="/u/Deathstalker"]:after,
a[href$="/u/sizont"]:after,
a[href$="/u/mastermeatlock"]:after,
a[href$="/u/pizzajesus"]:after,
a[href$="/u/collegeshitlord"]:after,
a[href$="/u/billyjackthemac"]:after,
a[href$="/u/CFR223"]:after,
a[href$="/u/HoLeeFupa"]:after,
a[href$="/u/S_t_e_r_l_i_n_g"]:after,
a[href$="/u/RanchFilledDonut"]:after,
a[href$="/u/ControlledBleeding"]:after,
a[href$="/u/Swolebroshitlord1"]:after,
a[href$="/u/Thor_McStuffins"]:after,
a[href$="/u/jobenzo2nd"]:after,
a[href$="/u/jhaluska"]:after,
a[href$="/u/PleaseDontSlowMeDown"]:after,
a[href$="/u/plonkplonk"]:after,
a[href$="/u/sacingham"]:after,
a[href$="/u/lasTRUMPcard"]:after,
a[href$="/u/SwimmingFox"]:after,
a[href$="/u/akrom"]:after,
a[href$="/u/ThoughtsAndPlayers"]:after,
a[href$="/u/Slagiatt"]:after,
a[href$="/u/MoltenFat"]:after,
a[href$="/u/Zoro152"]:after,
a[href$="/u/LWBG"]:after,
a[href$="/u/TheStapler"]:after,
a[href$="/u/CowboyDancer"]:after,
a[href$="/u/meklu"]:after,
a[href$="/u/paybythepound"]:after,
a[href$="/u/PsiloTheWolf"]:after,
a[href$="/u/Davicide"]:after,
a[href$="/u/redpilledblackguy"]:after,
a[href$="/u/Palindromedan"]:after,
a[href$="/u/Felez"]:after,
a[href$="/u/NotMrS"]:after,
a[href$="/u/PM_ME_UR_SOURCE_CODE"]:after,
a[href$="/u/E_Neutrality"]:after,
a[href$="/u/shatomirputin"]:after,
a[href$="/u/notarealperson"]:after,
a[href$="/u/veetack"]:after,
a[href$="/u/Calorie-Kin"]:after,
a[href$="/u/KingdomN"]:after,
a[href$="/u/ImLying"]:after,
a[href$="/u/Ellvarah"]:after,
a[href$="/u/julbe43"]:after,
a[href$="/u/fuoco"]:after,
a[href$="/u/TotalCult"]:after,
a[href$="/u/tom-bombadil"]:after,
a[href$="/u/IamtheDreadLobster"]:after,
a[href$="/u/speshul_snowflake"]:after,
a[href$="/u/nomi_malone"]:after,
a[href$="/u/Pathogenesis25"]:after,
a[href$="/u/Shitty_McShitlord"]:after,
a[href$="/u/BigBoss"]:after,
a[href$="/u/FrozenKlondyke"]:after,
a[href$="/u/Sythek"]:after,
a[href$="/u/vordster"]:after,
a[href$="/u/DoctorKoctor"]:after,
a[href$="/u/RobertPaulson"]:after,
a[href$="/u/wbfla"]:after,
a[href$="/u/Joebro88"]:after,
a[href$="/u/AndrossAngel"]:after,
a[href$="/u/swizzlesticks"]:after,
a[href$="/u/dcs2000"]:after,
a[href$="/u/silvester"]:after,
a[href$="/u/dontqueefonmebro"]:after,
a[href$="/u/door_"]:after,
a[href$="/u/TheEnzo"]:after,
a[href$="/u/wolflink009"]:after,
a[href$="/u/Invisible_Nomad"]:after,
a[href$="/u/Melbourne43"]:after,
a[href$="/u/Adler"]:after,
a[href$="/u/fatness"]:after,
a[href$="/u/cleftscout"]:after,
a[href$="/u/Maisy"]:after,
a[href$="/u/Eysenor"]:after,
a[href$="/u/GreyFox"]:after,
a[href$="/u/floris"]:after,
a[href$="/u/Morgasm"]:after,
a[href$="/u/GrimRipple"]:after,
a[href$="/u/xxlthrowaway"]:after,
a[href$="/u/sketchyadvice77"]:after,
a[href$="/u/Chodder"]:after,
a[href$="/u/diefatfucks"]:after,
a[href$="/u/CutTheCurby"]:after,
a[href$="/u/MyFatHateFlows"]:after,
a[href$="/u/uLookFatInThoseGenes"]:after,
a[href$="/u/Oveneise"]:after,
a[href$="/u/Elysium"]:after,
a[href$="/u/Special User"]:after
{ content: "Needs help using scissors";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/ShortWarrior"]:after,
a[href$="/u/LuciferCat"]:after,
a[href$="/u/Swoledamort"]:after,
a[href$="/u/technician90"]:after,
a[href$="/u/Fatty_McGoo"]:after,
a[href$="/u/zeonin"]:after,
a[href$="/u/HoodedHoodlum"]:after,
a[href$="/u/CheckYourFupa"]:after,
a[href$="/u/Kahlo"]:after,
a[href$="/u/tuxedo"]:after,
a[href$="/u/CyanRyan"]:after,
a[href$="/u/greenymaco"]:after,
a[href$="/u/CttCJim"]:after,
a[href$="/u/Landao"]:after,
a[href$="/u/fryabetes"]:after,
a[href$="/u/crimsonpowder"]:after,
a[href$="/u/tisi"]:after,
a[href$="/u/Era"]:after,
a[href$="/u/4kneecator"]:after,
a[href$="/u/shitlordstrugglez"]:after,
a[href$="/u/bkmnalpha"]:after,
a[href$="/u/larionov"]:after,
a[href$="/u/LoveThighGap"]:after,
a[href$="/u/hotmusician"]:after,
a[href$="/u/ILoveFPH"]:after,
a[href$="/u/Lenvaldier"]:after,
a[href$="/u/herr_scheisse"]:after,
a[href$="/u/FatPeopleHateMe"]:after,
a[href$="/u/Reddifugee"]:after,
a[href$="/u/orange-avocado"]:after,
a[href$="/u/Grimace_Reaper"]:after,
a[href$="/u/todbert"]:after,
a[href$="/u/ppbox"]:after,
a[href$="/u/thorgin"]:after,
a[href$="/u/Wolfthorn"]:after,
a[href$="/u/AlanWake"]:after,
a[href$="/u/QuillQuote"]:after,
a[href$="/u/Fallkniven"]:after,
a[href$="/u/CrackerBInebriated"]:after,
a[href$="/u/underthemotherboard"]:after,
a[href$="/u/redditHasCooties "]:after,
a[href$="/u/MC_BarelyLegible"]:after,
a[href$="/u/Lord_Shitlord"]:after,
a[href$="/u/bieberhole_69"]:after,
a[href$="/u/SetsAndReps"]:after,
a[href$="/u/FatPeopleHateAccount"]:after,
a[href$="/u/Daimao"]:after,
a[href$="/u/LJM"]:after,
a[href$="/u/ThinkingClear"]:after,
a[href$="/u/jrlascody"]:after,
a[href$="/u/iloveNoseRings"]:after,
a[href$="/u/firekarat"]:after,
a[href$="/u/PureFix"]:after,
a[href$="/u/diggeler"]:after,
a[href$="/u/yourhero7"]:after,
a[href$="/u/CttCJim"]:after,
a[href$="/u/cassis"]:after,
a[href$="/u/Shimmy"]:after,
a[href$="/u/joelmooner"]:after,
a[href$="/u/talones"]:after,
a[href$="/u/LazarusLong"]:after,
a[href$="/u/ogcook"]:after,
a[href$="/u/Allchiefedup24"]:after,
a[href$="/u/SouthPark"]:after,
a[href$="/u/BWBHAMMER"]:after,
a[href$="/u/archers_bows9"]:after,
a[href$="/u/Infiltrator"]:after,
a[href$="/u/Stinkybeetusfoot"]:after,
a[href$="/u/Anonymous_Coward"]:after,
a[href$="/u/danunit"]:after,
a[href$="/u/imnotyourfriendpal"]:after,
a[href$="/u/Tuna_n_Rice"]:after,
a[href$="/u/rshackleford252525"]:after,
a[href$="/u/CrackingYs"]:after,
a[href$="/u/the_foreigner"]:after,
a[href$="/u/raznog"]:after,
a[href$="/u/pretending_to_work"]:after,
a[href$="/u/alawn0204"]:after,
a[href$="/u/EndDrugAndOtherWars"]:after,
a[href$="/u/bloodygames"]:after,
a[href$="/u/THE_LAST_SHITLORD"]:after,
a[href$="/u/RedditThoughtPolice"]:after,
a[href$="/u/theunrighteous"]:after,
a[href$="/u/Officedrone"]:after,
a[href$="/u/Ajaxofbarbaria"]:after,
a[href$="/u/Yogus"]:after,
a[href$="/u/Honormyfupa"]:after,
a[href$="/u/NoTears4Fatties"]:after,
a[href$="/u/lionheart"]:after,
a[href$="/u/CustardsLastStand"]:after,
a[href$="/u/AlexanderGunther"]:after,
a[href$="/u/War_Wombat"]:after,
a[href$="/u/fsck"]:after,
a[href$="/u/kaO_rosseforP"]:after,
a[href$="/u/prisonersandpriests"]:after,
a[href$="/u/MissChenandlerBong"]:after,
a[href$="/u/Gigan"]:after,
a[href$="/u/ThisWeirdIndividual"]:after,
a[href$="/u/fupaccino"]:after,
a[href$="/u/Malek"]:after,
a[href$="/u/Nyte"]:after,
a[href$="/u/RlyRlyGoodlookn"]:after,
a[href$="/u/Just_talk"]:after,
a[href$="/u/4444"]:after,
a[href$="/u/Cartesian_Duelist"]:after,
a[href$="/u/dontdoxxmebro"]:after,
a[href$="/u/Hurt_Fee_Fees"]:after,
a[href$="/u/ShitLord-Vader"]:after,
a[href$="/u/mrwoo2010"]:after,
a[href$="/u/Mugen"]:after,
a[href$="/u/DoctorSpaceman"]:after,
a[href$="/u/Xenophero"]:after,
a[href$="/u/billdred"]:after,
a[href$="/u/Callisti"]:after,
a[href$="/u/The_Penis_Apprentice"]:after
{ content: "Has an Anime girlfriend";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/DatViet"]:after,
a[href$="/u/Miaiam"]:after,
a[href$="/u/LardHammer"]:after,
a[href$="/u/journalistsarelazy"]:after,
a[href$="/u/Shiny"]:after,
a[href$="/u/Chance"]:after,
a[href$="/u/smokratez"]:after,
a[href$="/u/Blooperman"]:after,
a[href$="/u/BoracicBaronetYr"]:after,
a[href$="/u/ShitlordLovesOreos"]:after,
a[href$="/u/Krewotic"]:after,
a[href$="/u/ChipSlap"]:after,
a[href$="/u/YikYak"]:after,
a[href$="/u/DrunkenPieRat"]:after,
a[href$="/u/TheShitlordBellossom"]:after,
a[href$="/u/Monsterbox"]:after,
a[href$="/u/Moudi"]:after,
a[href$="/u/Elcycs"]:after,
a[href$="/u/Tuna_n_Rice"]:after,
a[href$="/u/MrCrackALack"]:after,
a[href$="/u/antisugar"]:after,
a[href$="/u/KhanKhalifa"]:after,
a[href$="/u/green_man"]:after,
a[href$="/u/BigBadWolf"]:after,
a[href$="/u/Robert_Archer"]:after,
a[href$="/u/wmeth"]:after,
a[href$="/u/pbateman"]:after,
a[href$="/u/GinTrain"]:after,
a[href$="/u/shitwink"]:after,
a[href$="/u/C9"]:after,
a[href$="/u/Tomtortoise"]:after,
a[href$="/u/mk46gunner"]:after,
a[href$="/u/L1amas"]:after,
a[href$="/u/razzac11"]:after,
a[href$="/u/BonesTheJester"]:after,
a[href$="/u/droopy2525"]:after,
a[href$="/u/Umrtvovacz"]:after,
a[href$="/u/devoresekk"]:after,
a[href$="/u/shitlordAnthrax"]:after,
a[href$="/u/Wingedfoot13"]:after,
a[href$="/u/itazuka"]:after,
a[href$="/u/SirGutless"]:after,
a[href$="/u/Proverbs23"]:after,
a[href$="/u/LordShittington"]:after,
a[href$="/u/Usualsuspect"]:after,
a[href$="/u/ThisIsMyRealName"]:after,
a[href$="/u/PsychicTaco115"]:after,
a[href$="/u/ForTheTruth"]:after,
a[href$="/u/imaginareality"]:after,
a[href$="/u/The_ChosenOne"]:after,
a[href$="/u/WhaleWails"]:after,
a[href$="/u/BigBlackSock"]:after,
a[href$="/u/00ellis"]:after,
a[href$="/u/Thinnerprivilege"]:after,
a[href$="/u/ShitlordCaleb"]:after,
a[href$="/u/MrSaxoBeetus"]:after,
a[href$="/u/fryabeetus"]:after,
a[href$="/u/TunaAndCucumbers"]:after,
a[href$="/u/uvulectomy"]:after,
a[href$="/u/windingtables"]:after,
a[href$="/u/pm_me_your_excuses"]:after,
a[href$="/u/HamsAlwaysEatSnacks"]:after,
a[href$="/u/blackie"]:after,
a[href$="/u/Dacoon63"]:after,
a[href$="/u/LessRealsMoreFeels"]:after,
a[href$="/u/hulkingmanbeast"]:after,
a[href$="/u/Cool-it-Fatboy"]:after,
a[href$="/u/DishingShitLikeA"]:after,
a[href$="/u/Swole_is_life"]:after,
a[href$="/u/TehGlitch"]:after,
a[href$="/u/WildHamBeastTamer"]:after,
a[href$="/u/Apeabel"]:after,
a[href$="/u/DirtAddsHP"]:after,
a[href$="/u/Dueperdue"]:after,
a[href$="/u/theeyeisnotsatisfied"]:after,
a[href$="/u/hitlers_biggest_fan"]:after,
a[href$="/u/thatdamnchef"]:after,
a[href$="/u/Wwanker"]:after,
a[href$="/u/MetaTrauma_Shitlord"]:after,
a[href$="/u/allaboutthattreble"]:after,
a[href$="/u/FriedrichNietzsche"]:after,
a[href$="/u/PuddleGut"]:after,
a[href$="/u/Totenglocke"]:after,
a[href$="/u/aden"]:after,
a[href$="/u/inablackbox"]:after,
a[href$="/u/treyman780"]:after,
a[href$="/u/RippedSeTXshitlord"]:after,
a[href$="/u/DoctorShitlord_MD"]:after,
a[href$="/u/AlexanderBlack96"]:after,
a[href$="/u/Alephant"]:after,
a[href$="/u/CB750F"]:after,
a[href$="/u/ScreaminMime"]:after,
a[href$="/u/ObeseRedditAdmin"]:after,
a[href$="/u/entitledmoo"]:after,
a[href$="/u/Allergic_to_hams"]:after,
a[href$="/u/shitLordran"]:after,
a[href$="/u/fattyatemysympathy"]:after,
a[href$="/u/TheShitLordCynic"]:after,
a[href$="/u/Verified_Shitlord"]:after,
a[href$="/u/calcaliente"]:after,
a[href$="/u/D1Sun"]:after,
a[href$="/u/bloopton"]:after,
a[href$="/u/Hannabis"]:after,
a[href$="/u/GregorSamsa"]:after,
a[href$="/u/MathunBeag"]:after,
a[href$="/u/Jessee"]:after,
a[href$="/u/RapidLynx"]:after,
a[href$="/u/Calza"]:after,
a[href$="/u/Portable_Tits"]:after,
a[href$="/u/DANKGHIDORAH"]:after,
a[href$="/u/Nujabes"]:after,
a[href$="/u/Mjello"]:after,
a[href$="/u/Honey_Badger"]:after,
a[href$="/u/Qualia"]:after,
a[href$="/u/she"]:after
{ content: "Confuses left and right";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/G4"]:after,
a[href$="/u/moe"]:after,
a[href$="/u/JTtheGhost"]:after,
a[href$="/u/thegoldenboy"]:after,
a[href$="/u/TXeRunningMan"]:after,
a[href$="/u/Jimmy_Two_Fingers"]:after,
a[href$="/u/SilentMaster"]:after,
a[href$="/u/jonasbrotherfan69"]:after,
a[href$="/u/formerobeast"]:after,
a[href$="/u/FinallyLeftReddit"]:after,
a[href$="/u/FattyHater"]:after,
a[href$="/u/DieMafia"]:after,
a[href$="/u/FreedomToast"]:after,
a[href$="/u/nofatchix"]:after,
a[href$="/u/Theseu5"]:after,
a[href$="/u/DelusionalHominids"]:after,
a[href$="/u/Jeim"]:after,
a[href$="/u/ShitArchon"]:after,
a[href$="/u/FitSlav"]:after,
a[href$="/u/DecimateTheWeak"]:after,
a[href$="/u/KingMortales"]:after,
a[href$="/u/code_guerilla"]:after,
a[href$="/u/Raylan"]:after,
a[href$="/u/PuddleGut"]:after,
a[href$="/u/bunnyy"]:after,
a[href$="/u/ThinBlondeBeast"]:after,
a[href$="/u/professional_normie"]:after,
a[href$="/u/ScootyPoofTipper"]:after,
a[href$="/u/EatingSteak"]:after,
a[href$="/u/its-the-new-style"]:after,
a[href$="/u/unholymalachi"]:after,
a[href$="/u/conchpearls1"]:after,
a[href$="/u/shartlord"]:after,
a[href$="/u/BushClosedFPH"]:after,
a[href$="/u/monkeytennis"]:after,
a[href$="/u/Twentyonepointthree"]:after,
a[href$="/u/hiddencounter"]:after,
a[href$="/u/MarshmallowCreme"]:after,
a[href$="/u/Magusontwowheels"]:after,
a[href$="/u/SpeakNoReeevil"]:after,
a[href$="/u/SocialJustice_Wario"]:after,
a[href$="/u/FupaTupa"]:after,
a[href$="/u/WDTC1"]:after,
a[href$="/u/collegestudent24601"]:after,
a[href$="/u/dude_srsly"]:after,
a[href$="/u/thatonefag"]:after,
a[href$="/u/BuffyTheHampireSlayr"]:after,
a[href$="/u/GrandFupa"]:after,
a[href$="/u/sexypleurisy"]:after,
a[href$="/u/metalpetal"]:after,
a[href$="/u/Bunraku"]:after,
a[href$="/u/NerdButNotFat"]:after,
a[href$="/u/Seeker74"]:after,
a[href$="/u/A_Vile_Climate"]:after,
a[href$="/u/LiterallyLittering"]:after,
a[href$="/u/pezz"]:after,
a[href$="/u/TRIGGURED"]:after,
a[href$="/u/shadowassassinqueef"]:after,
a[href$="/u/Z3r0-C00l"]:after,
a[href$="/u/Shemadethis"]:after,
a[href$="/u/Unsung_Heroes"]:after,
a[href$="/u/Teddy36"]:after,
a[href$="/u/temp413"]:after,
a[href$="/u/FPH_Shitlord"]:after,
a[href$="/u/Magitek_X"]:after,
a[href$="/u/FFat20"]:after,
a[href$="/u/red_runner"]:after,
a[href$="/u/z91x"]:after,
a[href$="/u/The-Surgeon"]:after,
a[href$="/u/FUPA_TROOPA"]:after,
a[href$="/u/praivo"]:after,
a[href$="/u/MeltedSnowflake"]:after,
a[href$="/u/FatFuckery"]:after,
a[href$="/u/SurgicalShitlord"]:after,
a[href$="/u/ScheissKaiser"]:after,
a[href$="/u/Blacklightning"]:after,
a[href$="/u/DXK3"]:after,
a[href$="/u/Fitblue"]:after,
a[href$="/u/Itsforhismum"]:after,
a[href$="/u/squealingbravery"]:after,
a[href$="/u/Sandow"]:after,
a[href$="/u/LCplShitlord"]:after,
a[href$="/u/wut"]:after,
a[href$="/u/kuraisamurai"]:after,
a[href$="/u/redditHasCooties"]:after,
a[href$="/u/NoFatChics"]:after,
a[href$="/u/Dough-not"]:after,
a[href$="/u/Get_Some"]:after,
a[href$="/u/64bitfitdude"]:after,
a[href$="/u/Eatmyboot"]:after,
a[href$="/u/et_tu_beetus"]:after,
a[href$="/u/Not-a-goat"]:after,
a[href$="/u/pwn"]:after,
a[href$="/u/WhiskeyAlpha"]:after,
a[href$="/u/delusions"]:after,
a[href$="/u/hams_have_diabeetus"]:after,
a[href$="/u/Sniktun2"]:after,
a[href$="/u/brocklandersexgf"]:after,
a[href$="/u/dragonjujo"]:after,
a[href$="/u/THX_1138"]:after,
a[href$="/u/PhitPhil"]:after,
a[href$="/u/tucket1"]:after,
a[href$="/u/Izana"]:after,
a[href$="/u/OldRunningMan"]:after,
a[href$="/u/LeeryLucifer"]:after,
a[href$="/u/TeeHee"]:after,
a[href$="/u/WhiskeyAlpha8600"]:after,
a[href$="/u/SpookyFrank"]:after,
a[href$="/u/satnavtomington"]:after,
a[href$="/u/sh1tl0rd_of_ac1d"]:after,
a[href$="/u/statik"]:after,
a[href$="/u/ImTim"]:after,
a[href$="/u/the_spectre"]:after,
a[href$="/u/Fuckcensorship"]:after,
a[href$="/u/Phillyshitlord"]:after
{ content: "huffs paint";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/theepilepticferret"]:after,
a[href$="/u/sparklefuck"]:after,
a[href$="/u/BearJewAGH"]:after,
a[href$="/u/Sire"]:after,
a[href$="/u/ShitlordFoxmod"]:after,
a[href$="/u/AntiHam"]:after,
a[href$="/u/Naziadolfhitler"]:after,
a[href$="/u/RollCakeTroll"]:after,
a[href$="/u/dodecadildo"]:after,
a[href$="/u/AmIRelevantYet"]:after,
a[href$="/u/TwoWholePizzas"]:after,
a[href$="/u/bigeasy"]:after,
a[href$="/u/cyclops1771"]:after,
a[href$="/u/sonic_sabbath"]:after,
a[href$="/u/dutchguy7"]:after,
a[href$="/u/pandaman212"]:after,
a[href$="/u/Tinedmovie4062"]:after,
a[href$="/u/MegaShitFactory"]:after,
a[href$="/u/totalitarianism"]:after,
a[href$="/u/JeepGuy79"]:after,
a[href$="/u/00pimp"]:after,
a[href$="/u/DarkLordofTheShit"]:after,
a[href$="/u/dickpork"]:after,
a[href$="/u/fuckthefatties24"]:after,
a[href$="/u/denko-chan"]:after,
a[href$="/u/EATMOAR"]:after,
a[href$="/u/olzsla"]:after,
a[href$="/u/TheOlu"]:after,
a[href$="/u/lefthandpath"]:after,
a[href$="/u/JiminyShitlord"]:after,
a[href$="/u/JustAnotherShitlord"]:after,
a[href$="/u/TheGreatLenov"]:after,
a[href$="/u/Mellowjell-o"]:after,
a[href$="/u/rotten_ronny"]:after,
a[href$="/u/fat_cunt_stunt_punt"]:after,
a[href$="/u/landwhaleintolerance"]:after,
a[href$="/u/narwic"]:after,
a[href$="/u/Vermality"]:after,
a[href$="/u/Kpeen"]:after,
a[href$="/u/Usualsuspect"]:after,
a[href$="/u/landwhaleintolerance"]:after,
a[href$="/u/captainbuttpirate"]:after,
a[href$="/u/Cow_Police"]:after,
a[href$="/u/3rdworld"]:after,
a[href$="/u/fek_sinjoro"]:after,
a[href$="/u/RickyStreetshitter"]:after,
a[href$="/u/XenoClimber"]:after,
a[href$="/u/Fooj"]:after,
a[href$="/u/BaronVonThunderBolt"]:after,
a[href$="/u/Delorean1988"]:after,
a[href$="/u/tsasa"]:after,
a[href$="/u/dabsareking"]:after,
a[href$="/u/gaylordshitlord"]:after,
a[href$="/u/Goater"]:after,
a[href$="/u/Stopthefatness"]:after,
a[href$="/u/vault_boy"]:after,
a[href$="/u/C11H15No2"]:after,
a[href$="/u/thatonefag"]:after,
a[href$="/u/HamSalad"]:after,
a[href$="/u/GainsGoblinGoebbels"]:after,
a[href$="/u/PocketSized"]:after,
a[href$="/u/lclif"]:after,
a[href$="/u/its-the-new-style"]:after,
a[href$="/u/Lopsid"]:after,
a[href$="/u/conchpearls1"]:after,
a[href$="/u/ScootyPoofTipper"]:after,
a[href$="/u/Psyrinx"]:after,
a[href$="/u/Dougal_McHaggis"]:after,
a[href$="/u/Volksgemeinschaft"]:after,
a[href$="/u/interflop"]:after,
a[href$="/u/ShitLordWaifu"]:after,
a[href$="/u/monkeytennis"]:after,
a[href$="/u/Ilisyer"]:after,
a[href$="/u/CharlesMay"]:after,
a[href$="/u/DevilsMonkey"]:after,
a[href$="/u/David_Bains_Jumper"]:after,
a[href$="/u/MarshmallowCreme"]:after,
a[href$="/u/HitlerDinduNufin"]:after,
a[href$="/u/hiddencounter"]:after,
a[href$="/u/Magusontwowheels"]:after,
a[href$="/u/Kaleidowave"]:after,
a[href$="/u/theJshow"]:after,
a[href$="/u/FupaTupa"]:after,
a[href$="/u/WDTC1"]:after,
a[href$="/u/Jimbonez_Jonez"]:after,
a[href$="/u/Condi_Shaun"]:after,
a[href$="/u/NoFun"]:after,
a[href$="/u/niallmurphytdub"]:after,
a[href$="/u/Pyrrha191"]:after,
a[href$="/u/ZaphodUnderpants"]:after,
a[href$="/u/ETres"]:after,
a[href$="/u/BeetJuice"]:after,
a[href$="/u/nosensemakes"]:after,
a[href$="/u/FightThisFire"]:after,
a[href$="/u/Youfatfuck"]:after,
a[href$="/u/eroln"]:after,
a[href$="/u/8BigMacNMuhDietCoke"]:after,
a[href$="/u/1159"]:after,
a[href$="/u/SaveTheChildren"]:after,
a[href$="/u/ineedbettername"]:after,
a[href$="/u/Fllmia"]:after,
a[href$="/u/Adolf_Lifter"]:after,
a[href$="/u/EnrichedPiano"]:after,
a[href$="/u/JhonCatus"]:after,
a[href$="/u/SocratesOP"]:after,
a[href$="/u/aquaticteabag"]:after,
a[href$="/u/subsonic0702"]:after,
a[href$="/u/CanadianPucker"]:after,
a[href$="/u/Densz"]:after,
a[href$="/u/OnePaunchMan"]:after,
a[href$="/u/what_the_fudge"]:after,
a[href$="/u/AnyColourYouLike"]:after,
a[href$="/u/Anti-Social"]:after,
a[href$="/u/1stMillenial"]:after,
a[href$="/u/That_wont_do_pig"]:after 
{ content: "Subscribed to the Daily Mail";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/Ruston"]:after,
a[href$="/u/PetChan"]:after,
a[href$="/u/mmmmdonuts"]:after,
a[href$="/u/Sylph"]:after,
a[href$="/u/Scratchie"]:after,
a[href$="/u/NoMeGustanLosNiggers"]:after,
a[href$="/u/RogerByam"]:after,
a[href$="/u/raw"]:after,
a[href$="/u/hamplanetarium1"]:after,
a[href$="/u/Beautyinblue"]:after,
a[href$="/u/Man_from_B_E_E_T_U_S"]:after,
a[href$="/u/AzarelDJ"]:after,
a[href$="/u/gaussian"]:after,
a[href$="/u/retoasted"]:after,
a[href$="/u/Shieldmaden"]:after,
a[href$="/u/Fancyajellybaby"]:after,
a[href$="/u/MajorasAss"]:after,
a[href$="/u/picklesforever"]:after,
a[href$="/u/rompele"]:after,
a[href$="/u/SunLala298"]:after,
a[href$="/u/DelicateDevotchka"]:after,
a[href$="/u/Thepiggering"]:after,
a[href$="/u/Secretly_psycho"]:after,
a[href$="/u/NotYourDoctor"]:after,
a[href$="/u/mintfleur"]:after,
a[href$="/u/FickleFlame107"]:after,
a[href$="/u/Jamvoat"]:after,
a[href$="/u/Jasdecoy"]:after,
a[href$="/u/Princess_Shitlady"]:after,
a[href$="/u/ToeKink"]:after,
a[href$="/u/Kuroi"]:after,
a[href$="/u/rabm"]:after,
a[href$="/u/Kvnt"]:after,
a[href$="/u/meowilicious"]:after,
a[href$="/u/Atsuki"]:after,
a[href$="/u/Lady-Stoneheart"]:after,
a[href$="/u/Hellad0pe"]:after,
a[href$="/u/qj27"]:after,
a[href$="/u/shitlordnurse"]:after,
a[href$="/u/Littleahsoka"]:after,
a[href$="/u/little_red"]:after,
a[href$="/u/PenguinOrgy"]:after,
a[href$="/u/softs"]:after,
a[href$="/u/blackdovespeaks"]:after,
a[href$="/u/helathin"]:after,
a[href$="/u/Fupachabra"]:after,
a[href$="/u/itsmeyoursister"]:after,
a[href$="/u/bgt8"]:after,
a[href$="/u/pateachoux"]:after,
a[href$="/u/Placetohide"]:after,
a[href$="/u/Siacca"]:after,
a[href$="/u/Punkte"]:after,
a[href$="/u/alagra"]:after,
a[href$="/u/OinkOink"]:after,
a[href$="/u/tweedles"]:after,
a[href$="/u/ThotsAndPrayers"]:after,
a[href$="/u/isol8"]:after,
a[href$="/u/StickGirl"]:after,
a[href$="/u/bluejade"]:after,
a[href$="/u/HomosexualPotatoes"]:after,
a[href$="/u/intermittentfeasting"]:after,
a[href$="/u/Urgan-nagru"]:after,
a[href$="/u/GreffeduFoie"]:after,
a[href$="/u/SlowResponseTime"]:after,
a[href$="/u/Shitwherever"]:after,
a[href$="/u/OrganicEggWhite"]:after,
a[href$="/u/ScarletNite"]:after,
a[href$="/u/Somnivangelist"]:after,
a[href$="/u/bethygal83"]:after,
a[href$="/u/BisonBiff"]:after,
a[href$="/u/EffYourDuckAss"]:after,
a[href$="/u/FPHMistress"]:after,
a[href$="/u/anotherfattyhater"]:after,
a[href$="/u/ConnieDeShuns"]:after,
a[href$="/u/FPHForever"]:after,
a[href$="/u/thisuhatesyou"]:after,
a[href$="/u/i_am_the_ginger"]:after,
a[href$="/u/GenevieveJenkins"]:after,
a[href$="/u/eat_a_dick_por_favor"]:after,
a[href$="/u/ActualHourglass"]:after,
a[href$="/u/Thinchick"]:after,
a[href$="/u/fatis4punching"]:after,
a[href$="/u/strings"]:after,
a[href$="/u/aretemis"]:after,
a[href$="/u/redherpbluederp"]:after,
a[href$="/u/Trickster"]:after,
a[href$="/u/32DDbitches"]:after,
a[href$="/u/Entitilitus"]:after,
a[href$="/u/MasterBettyPain"]:after,
a[href$="/u/dotty"]:after,
a[href$="/u/Skinny_McJiggles"]:after,
a[href$="/u/naked_ditchdigger"]:after,
a[href$="/u/SacoDeHuesos"]:after,
a[href$="/u/HonorYourBeetus"]:after,
a[href$="/u/Antimony"]:after,
a[href$="/u/shitladybird"]:after,
a[href$="/u/commandershitlorde"]:after,
a[href$="/u/SassyShitlady"]:after,
a[href$="/u/fearsnight"]:after,
a[href$="/u/redjenny"]:after,
a[href$="/u/Thippe"]:after,
a[href$="/u/Catcat"]:after,
a[href$="/u/longlostbleu"]:after,
a[href$="/u/wolfgirlnaya"]:after,
a[href$="/u/TheSashimiTamale"]:after,
a[href$="/u/VegetarianZombie1"]:after,
a[href$="/u/absmom20"]:after,
a[href$="/u/IAHA"]:after,
a[href$="/u/OgreSounds"]:after,
a[href$="/u/Gidg"]:after,
a[href$="/u/DatVitaminD"]:after,
a[href$="/u/dotty"]:after,
a[href$="/u/nothinggoddammit"]:after,
a[href$="/u/horse__tornado"]:after,
a[href$="/u/fabulousalpaca"]:after 
{ content: "Is actually a dude IRL";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/Unsung_Heroes_again"]:after,
a[href$="/u/Celtic_Queen"]:after,
a[href$="/u/SeethingHatred"]:after,
a[href$="/u/seniorscubasquid"]:after,
a[href$="/u/SeeYouNextTuesday"]:after,
a[href$="/u/iscrapedmyknee"]:after,
a[href$="/u/ShiteLorde"]:after,
a[href$="/u/masyday"]:after,
a[href$="/u/LeanMeanShitQueen"]:after,
a[href$="/u/FatJavalina"]:after,
a[href$="/u/nwo-chan"]:after,
a[href$="/u/miss_ann_thrope"]:after,
a[href$="/u/MeeblesMerble"]:after,
a[href$="/u/Randomninja"]:after,
a[href$="/u/darkmuffin"]:after,
a[href$="/u/valkyrieevergreen"]:after,
a[href$="/u/Fishgoose"]:after,
a[href$="/u/BuzzingBeaver"]:after,
a[href$="/u/thinbulina"]:after,
a[href$="/u/Dropkickbooties"]:after,
a[href$="/u/wolfgangiv"]:after,
a[href$="/u/pug_life"]:after,
a[href$="/u/GreenKitty"]:after,
a[href$="/u/morbidly_teehees"]:after,
a[href$="/u/maliblue"]:after,
a[href$="/u/ivegotaqueso"]:after,
a[href$="/u/znikole"]:after,
a[href$="/u/Nodra"]:after,
a[href$="/u/CaloricKarma"]:after,
a[href$="/u/CakeTrap"]:after,
a[href$="/u/fatpeopleh8_dotcom"]:after,
a[href$="/u/PrettyPeach"]:after,
a[href$="/u/HamTaro"]:after,
a[href$="/u/madam_psycho_sexy"]:after,
a[href$="/u/christy"]:after,
a[href$="/u/Ch3ck3rs"]:after,
a[href$="/u/shitmom"]:after,
a[href$="/u/Red_witch"]:after,
a[href$="/u/HarpoonTheWhales"]:after,
a[href$="/u/SkinnyVanillaLatte"]:after,
a[href$="/u/Tensor_Fasciae_Latte"]:after,
a[href$="/u/Fatblaster2000"]:after,
a[href$="/u/bellylugosi"]:after,
a[href$="/u/sharkxie"]:after,
a[href$="/u/pedestrian_x"]:after,
a[href$="/u/ICanWipeMyOwnAss"]:after,
a[href$="/u/Buggsie_Blue"]:after,
a[href$="/u/Size0YogaPants"]:after,
a[href$="/u/DietCokehead1"]:after,
a[href$="/u/Brightness"]:after,
a[href$="/u/Fatkini"]:after,
a[href$="/u/fattieboom"]:after,
a[href$="/u/Laughingllama"]:after,
a[href$="/u/putdownthedonut"]:after,
a[href$="/u/honormyacanthosis"]:after,
a[href$="/u/newbuggy"]:after,
a[href$="/u/PepeThePained"]:after,
a[href$="/u/8-BIT_Ruby"]:after,
a[href$="/u/Rimfakse"]:after,
a[href$="/u/Smartt88"]:after,
a[href$="/u/iheartmypuppy"]:after,
a[href$="/u/TheThinSister"]:after,
a[href$="/u/shortspice"]:after,
a[href$="/u/Babynachollama"]:after,
a[href$="/u/vanitysize00"]:after,
a[href$="/u/fuckredditcensorship"]:after,
a[href$="/u/FoxForce_Five"]:after,
a[href$="/u/WileyECryote"]:after,
a[href$="/u/baddreamstonight"]:after,
a[href$="/u/The_Lady_Galahad"]:after,
a[href$="/u/andsoitgoes"]:after,
a[href$="/u/Missfit"]:after,
a[href$="/u/FPHrefugee"]:after,
a[href$="/u/tinycicada"]:after,
a[href$="/u/WiredBones"]:after,
a[href$="/u/ObeseObituary"]:after,
a[href$="/u/ilieksnow"]:after,
a[href$="/u/EatYourKimchi"]:after,
a[href$="/u/codeverydamnday"]:after,
a[href$="/u/Laurendark"]:after,
a[href$="/u/canarynoir"]:after,
a[href$="/u/Silverstaryu"]:after,
a[href$="/u/pomegranate"]:after,
a[href$="/u/hornypickle"]:after,
a[href$="/u/sociallyanxious"]:after,
a[href$="/u/brachiosaurus_"]:after,
a[href$="/u/canarynoir"]:after,
a[href$="/u/ridsloth"]:after,
a[href$="/u/curvygirl"]:after,
a[href$="/u/cultural_dissenter"]:after,
a[href$="/u/thelonelybench"]:after,
a[href$="/u/Skinnyphat_sleestak"]:after,
a[href$="/u/SweetStormy"]:after,
a[href$="/u/McDoublechins"]:after,
a[href$="/u/twhitucr"]:after,
a[href$="/u/thighgapgoddess"]:after,
a[href$="/u/Thinnerprivilege"]:after,
a[href$="/u/ur_gradeschool_crush"]:after,
a[href$="/u/clockworkgirl21"]:after,
a[href$="/u/moistFUPAcheeze"]:after,
a[href$="/u/hi5"]:after,
a[href$="/u/HorsesHateHams"]:after,
a[href$="/u/rainbow_ashtray"]:after,
a[href$="/u/MaryJaneDoe"]:after,
a[href$="/u/Makattack"]:after,
a[href$="/u/shezbot"]:after,
a[href$="/u/peripatetic"]:after,
a[href$="/u/RedhairedLemur"]:after,
a[href$="/u/nikesandheels"]:after,
a[href$="/u/CertifiedShitlord"]:after,
a[href$="/u/MolotovCocktail"]:after,
a[href$="/u/FuckingEatLess"]:after,
a[href$="/u/Slybunny"]:after,
a[href$="/u/ChilledPorn"]:after,
a[href$="/u/hypercat"]:after
{ content: "Unironically a flat Earther";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/DopeandDiamonds"]:after,
a[href$="/u/WestEndGirl"]:after,
a[href$="/u/CIShitLord"]:after,
a[href$="/u/Runway22L"]:after,
a[href$="/u/Gitoffmuhlawn"]:after,
a[href$="/u/libertas_aut_mors"]:after,
a[href$="/u/Donutday"]:after,
a[href$="/u/Fuck-off-fatties"]:after,
a[href$="/u/Chronicallydieting"]:after,
a[href$="/u/Cyracs"]:after,
a[href$="/u/SSfriendship"]:after,
a[href$="/u/jdkthekid"]:after,
a[href$="/u/shadybrainfarm"]:after,
a[href$="/u/ThisIsMyAngerAccount"]:after,
a[href$="/u/proteinfordays"]:after,
a[href$="/u/jennyanydots817"]:after,
a[href$="/u/Captain_Janeway"]:after,
a[href$="/u/Fictura"]:after,
a[href$="/u/HasSelfControl"]:after,
a[href$="/u/DLmorethanu"]:after,
a[href$="/u/Masshole_shitlady"]:after,
a[href$="/u/HamilySpawn"]:after,
a[href$="/u/kauaikauaikauai"]:after,
a[href$="/u/miqotes"]:after,
a[href$="/u/BuzzingBeaver2"]:after,
a[href$="/u/capricious"]:after,
a[href$="/u/Coffeecat"]:after,
a[href$="/u/PrivilegedHealthist"]:after,
a[href$="/u/whatsatornado"]:after,
a[href$="/u/fatefish"]:after,
a[href$="/u/BangBangBoom"]:after,
a[href$="/u/Stubby"]:after,
a[href$="/u/BlkGrlKnickers"]:after,
a[href$="/u/drink_some_water"]:after,
a[href$="/u/PraiseBeToBeetus"]:after,
a[href$="/u/Shitlady_on_Wheels"]:after,
a[href$="/u/stupidlikeafox"]:after,
a[href$="/u/hamsbegone"]:after,
a[href$="/u/Abbytheobesemanx"]:after,
a[href$="/u/bananaelf"]:after,
a[href$="/u/Bureaucrat_36"]:after,
a[href$="/u/Buttress_of_windsor"]:after,
a[href$="/u/ElectricPurple"]:after,
a[href$="/u/icantstopeatingpizza"]:after,
a[href$="/u/mangiamerdeemorte"]:after,
a[href$="/u/PaoShadowBannedMe"]:after,
a[href$="/u/RoundTwoElectric"]:after,
a[href$="/u/Missingpiece"]:after,
a[href$="/u/Kappyten"]:after,
a[href$="/u/FatLoadOfCobblers"]:after,
a[href$="/u/FatShamingShitLady"]:after,
a[href$="/u/IttyBittyKitty"]:after,
a[href$="/u/goddamnroommate"]:after,
a[href$="/u/skinniemouse"]:after,
a[href$="/u/Corruption22"]:after,
a[href$="/u/starwalker"]:after,
a[href$="/u/mountainclimber"]:after,
a[href$="/u/thinsignificant"]:after,
a[href$="/u/Agrajag_"]:after,
a[href$="/u/SOS_roommateapotamus"]:after,
a[href$="/u/SoylentGreenday"]:after,
a[href$="/u/mstumblrinafupa"]:after,
a[href$="/u/PsychoSkinnyBitch"]:after,
a[href$="/u/Voatoxoverbotox"]:after,
a[href$="/u/Meadow"]:after,
a[href$="/u/lavaliere"]:after,
a[href$="/u/jimmorridumb"]:after,
a[href$="/u/Doorknobshurtmybones"]:after,
a[href$="/u/minerva109"]:after,
a[href$="/u/bukowskis_bluebird"]:after,
a[href$="/u/nonofattyno"]:after,
a[href$="/u/MagickCat"]:after,
a[href$="/u/Fentiaz"]:after,
a[href$="/u/invisiblecalories"]:after,
a[href$="/u/SugarPie"]:after,
a[href$="/u/stercorisdomina"]:after,
a[href$="/u/strawberryshitlady"]:after,
a[href$="/u/TunaFishTroubles"]:after,
a[href$="/u/babababacon"]:after,
a[href$="/u/bvoid"]:after,
a[href$="/u/lalalalourdes"]:after,
a[href$="/u/buttmuffins123"]:after,
a[href$="/u/KitKatLasagna55"]:after,
a[href$="/u/a_p"]:after,
a[href$="/u/SluttyBrownie"]:after,
a[href$="/u/totalbitch"]:after,
a[href$="/u/samantha721"]:after,
a[href$="/u/skinnyfattofit"]:after,
a[href$="/u/AppleSlice"]:after,
a[href$="/u/sniper_wolf"]:after,
a[href$="/u/BunnytheSlayer"]:after,
a[href$="/u/Brights"]:after,
a[href$="/u/BulimicBarbie"]:after,
a[href$="/u/Brunella"]:after,
a[href$="/u/mielikki"]:after,
a[href$="/u/deuxabuse"]:after,
a[href$="/u/LessBingeMorePurge"]:after,
a[href$="/u/transfit"]:after,
a[href$="/u/Lynx"]:after,
a[href$="/u/laurenrawrface"]:after,
a[href$="/u/Supersecretgf"]:after,
a[href$="/u/lovechaitea"]:after,
a[href$="/u/lll------lll"]:after,
a[href$="/u/grapefruitforever"]:after,
a[href$="/u/stealthyfox"]:after,
a[href$="/u/CherryLime"]:after,
a[href$="/u/ballsacks"]:after,
a[href$="/u/wearenotgoingleft"]:after,
a[href$="/u/JustAnotherShitlady"]:after,
a[href$="/u/Adi-opposed"]:after,
a[href$="/u/shrinkydinks"]:after,
a[href$="/u/Lapis-Lazuli"]:after,
a[href$="/u/lardcats"]:after,
a[href$="/u/EvilCookie"]:after,
a[href$="/u/HateCumbuckets"]:after
{ content: "Verified Shitlady";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[href$="/u/TiggerNits"]:after,
a[href$="/u/Mike_1990_tx"]:after,
a[href$="/u/Rokuah"]:after,
a[href$="/u/AbjectSubstance"]:after,
a[href$="/u/fatsruineverything"]:after,
a[href$="/u/PeaceLoveAndRamen"]:after,
a[href$="/u/Dildoe_Swagginz"]:after,
a[href$="/u/Syphrosyne"]:after,
a[href$="/u/obesitarp"]:after,
a[href$="/u/santisimamuerte"]:after,
a[href$="/u/In_the_making"]:after,
a[href$="/u/Ellvarah"]:after,
a[href$="/u/dotdashdashdot"]:after,
a[href$="/u/la_fupacabra"]:after,
a[href$="/u/Thinnerbeauty666"]:after,
a[href$="/u/Shitladyopossum"]:after,
a[href$="/u/tinyrunningshorts"]:after,
a[href$="/u/coffeeandmetal"]:after,
a[href$="/u/Happy_snappy"]:after,
a[href$="/u/Hume"]:after,
a[href$="/u/WhatTheFat"]:after,
a[href$="/u/HippyHoney"]:after,
a[href$="/u/proteinfordays"]:after,
a[href$="/u/OhTheHamanatee"]:after,
a[href$="/u/burntfishnchips"]:after,
a[href$="/u/oreovegan"]:after,
a[href$="/u/Masshole_shitlady"]:after,
a[href$="/u/Lurkerontheroof"]:after,
a[href$="/u/ZB122"]:after,
a[href$="/u/TimePulse"]:after,
a[href$="/u/Bunnnnnnn"]:after,
a[href$="/u/sanseveria"]:after,
a[href$="/u/wuzhao"]:after,
a[href$="/u/Foxyloxy"]:after,
a[href$="/u/Beetusalert"]:after,
a[href$="/u/juggornot"]:after,
a[href$="/u/Happy_snappy"]:after,
a[href$="/u/sizedouttaZero"]:after,
a[href$="/u/ThaiChai"]:after,
a[href$="/u/Nanoquark"]:after,
a[href$="/u/LightAsFeathers"]:after,
a[href$="/u/code187"]:after,
a[href$="/u/PM-me-your-PG-tips"]:after,
a[href$="/u/fattyboomboom"]:after,
a[href$="/u/Yesvape3"]:after,
a[href$="/u/kraftykat"]:after,
a[href$="/u/Fat_chance"]:after,
a[href$="/u/averagefoxy"]:after,
a[href$="/u/squirrelette"]:after,
a[href$="/u/Cabellista"]:after,
a[href$="/u/Taehyung"]:after,
a[href$="/u/Smaller"]:after,
a[href$="/u/LolturdFerguson"]:after,
a[href$="/u/laughing_90"]:after,
a[href$="/u/sharkzard"]:after,
a[href$="/u/GoldenPhoenix"]:after,
a[href$="/u/shitlady123"]:after,
a[href$="/u/shittycyclist"]:after,
a[href$="/u/HammyFlammy"]:after,
a[href$="/u/thighgapandcurves"]:after,
a[href$="/u/SevenDaysTooLong"]:after,
a[href$="/u/Sour_Kraut"]:after,
a[href$="/u/Aniabub"]:after,
a[href$="/u/lockedinlace"]:after,
a[href$="/u/RedStilettoes"]:after,
a[href$="/u/polingforabs"]:after,
a[href$="/u/nyLxx"]:after,
a[href$="/u/Pyhooya"]:after,
a[href$="/u/Pullmypork"]:after,
a[href$="/u/Redkraken"]:after,
a[href$="/u/Sugarfreeyogi"]:after,
a[href$="/u/diacetylmorfine"]:after,
a[href$="/u/Sharra"]:after,
a[href$="/u/unikko"]:after,
a[href$="/u/curves-shmurves"]:after,
a[href$="/u/Elumie"]:after,
a[href$="/u/BarbieBitch"]:after,
a[href$="/u/CakeDealer"]:after,
a[href$="/u/hellno"]:after,
a[href$="/u/Countess_shitula"]:after
a[href$="/u/deadthings"]:after
{ content: "Verified Shitlady";color: white !important;padding: 3px !important;border: 0px !important;border-radius: 5px !important;text-shadow: 1px 1px 1px #000, -1px -1px 1px #000;background: linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -webkit-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;background: -moz-linear-gradient(left,#ff0033,#ff00dd,#4000ff,#00eaff,#00ff22,#ffff00,#ff9100) !important;animation: rainbowbar 1s linear infinite;-webkit-animation: rainbowbar 1s linear infinite; }

a[title="Profile"]:after,a.upvoatsGiven:after{content:none;}
