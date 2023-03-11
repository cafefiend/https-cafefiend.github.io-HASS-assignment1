Skip to content
Search or jump to…
Pull requests
Issues
Codespaces
Marketplace
Explore
 
@cafefiend 
cafefiend
/
HASS-assignment1
Public
Cannot fork because you own this repository and are not a member of any organizations.
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
HASS-assignment1/Assignment2-JaniceYoung.html
@cafefiend
cafefiend Add files via upload
Latest commit 4d28e94 18 minutes ago
 History
 1 contributor
120 lines (108 sloc)  3.51 KB

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Interactive Data Visualisation Assignment 2</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Lato:wght@300&family=Libre+Franklin:wght@400;600&display=swap" rel="stylesheet"> 

    <!-- CSS -->
    <style>
        /*Text formatting etc.*/
        html {
            font-size: 18px;
        }
        body {
            /*Gruvbox-Light colors*/
            --bg0: #fbf1c7;   --fg0: #282828;
            --bg1: #ebdbb2;   --fg1: #3c3836;
            --bg2: #d5c4a1;   --fg2: #504945;
            --bg3: #bdae93;   --fg3: #665c54;
            --bg4: #a89984;   --fg4: #7c6f64;
            --red: #cc241d; --red_d: #9d0006;
            --org: #d65d0e; --org_d: #af3a03;
            --ylw: #d79921; --ylw_d: #b57614;
            --grn: #98971a; --grn_d: #79740e;
            --blu: #458588; --blu_d: #076678;
            --prp: #b16286; --prp_d: #8f3f71;
            --aqa: #689d6a; --aqa_d: #427b58;
            --gry: #7c6f64; --gry_d: #928374;
            background: white;
            color: var(--fg0);
            font-family: 'Lato', 'Arial', monospace;
            font-size: 1rem;
            line-height: 150%;
            text-align: justify;
            text-justify: inter-word;
        }
        h1, h2, h3, h4, h5 {
            font-family: 'Libre Franklin', 'Arial', sans-serif;
        }
        h5 {
            font-family: 'Lato';
            font-size: 1rem;
        }

        /* Link formatting */
        a:link {color: var(--org_d);text-decoration: none;}
        a:visited {color: var(--red);}
        a:hover {color: var(--org);}

        /*Image formatting*/
        img {
            display: block;
            max-height: 400px;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
        }

        /* Simple flexbox */
        .grid{
            width: 90%;
            max-width: 952px;
            margin: 0 auto;
        }
        .block{
            display: block;
            padding: 20px 0;
        }
        .col-33{
            width: 33.3%;
            float: left;
        }
        .col-50{
            width: 50%;
            float: left;
        }
        .gutter{
            margin-left: 20px;
            margin-right: 20px;
        }
        .clear{
            clear: both;
            display: block;
        }
        @media all and (max-width:800px) {
            .col-33{
                width: 50%;
            }
        }
        @media all and (max-width:800px) {
            .col-33{
                width: 50%;
            }
        }
    </style>
</head>

<body>
    <div class="grid">

        <h2>Interactive Data Visualisation</h2>
        <h4>Assignment 2</h3>

    <iframe src="https://sutdapac-my.sharepoint.com/personal/janice_young_mymail_sutd_edu_sg/_layouts/15/Doc.aspx?sourcedoc={b3c29d24-f13a-4a8f-965d-118c8734649e}&amp;action=embedview&amp;wdAr=1.7777777777777777&amp;wdEaaCheck=1" width="952px" height="576px" frameborder="0">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>
    
    <div class="grid"></div>

    <footer>
        <p>Janice Young S/No. 1007341
        <br>Interactive Data Visualisation</p>
        </footer>
        </div>
        
        </body>
        </html>
        
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
HASS-assignment1/Assignment2-JaniceYoung.html at main · cafefiend/HASS-assignment1
