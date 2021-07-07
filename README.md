# James' CV
![Update publications](https://github.com/James11222/James_CV/actions/workflows/update_pubs.yml/badge.svg)


This repo offers an automation to updating a CV with publications. This repo was modified from Arjun Savel's original repo. 

The formatting of my CV is also based on @davidwhogg's, and the implementation of continuous integration was inspired by @dfm's.

## Process

Every 24 Hours, `scrape_ads` is run, which pulls my publications & their citations from [NASA ADS](https://ui.adsabs.harvard.edu/). These are aggregated, formatted, and written to a tex file. 


<object data="https://github.com/James11222/James_CV/blob/1dcebc0dcd537eebc589c27f784d05adca4defc7/James__CV-4.pdf" type="application/pdf" width="700px" height="700px">
    <embed src="https://github.com/James11222/James_CV/blob/1dcebc0dcd537eebc589c27f784d05adca4defc7/James__CV-4.pdf">
        <p>This browser does not support inline PDFs. Please download the PDF to view it: <a href="https://github.com/James11222/James_CV/blob/1dcebc0dcd537eebc589c27f784d05adca4defc7/James__CV-4.pdf">Download PDF</a>.</p>
    </embed>
</object>
