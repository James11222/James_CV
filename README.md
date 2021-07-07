# James' CV
![Update publications](https://github.com/James11222/James_CV/actions/workflows/update_pubs.yml/badge.svg)


This repo offers an automation to updating a CV with publications. This repo was modified from Arjun Savel's original repo. 

The formatting of my CV is also based on @davidwhogg's, and the implementation of continuous integration was inspired by @dfm's.

## Process

Every 24 Hours, `scrape_ads` is run, which pulls my publications & their citations from [NASA ADS](https://ui.adsabs.harvard.edu/). These are aggregated, formatted, and written to a tex file. 


<!-- <object data="http://yoursite.com/the.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="http://yoursite.com/the.pdf">
        <p>This browser does not support PDFs. Please download the PDF to view it: <a href="http://yoursite.com/the.pdf">Download PDF</a>.</p>
    </embed>
</object> -->
