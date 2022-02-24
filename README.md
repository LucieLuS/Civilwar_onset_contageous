# Civilwar_onset_contageous

## Archer:

### remember to change country name, date and key accordingly
"https://archerapi.clinecenter.illinois.edu/select?q=content:(Algeria%20AND%20(%22civil%20war%22%20OR%20%22internal%20conflict%22%20OR%20%22internal%20war%22%20OR%20%22civil%20conflict%22)%20AND%20publication_date:[2015-05-20T00:00:00Z%20TO%202015-08-20T23:59:59Z])&rows=1000&fl=aid,publication_date,title,url,publisher,country,status,source_name&source_name:BulkLexisNexis%20OR%20BulkLexisNexis_v2&wt=csv&key=YOURKEYS"


## Civil war dataset:
UCDP UCDP/PRIO Armed Conflict Dataset Codebook:  UCDP datasets have always relied on the 25 deaths in a calendar year threshold for inclusion in its datasets. A link to its codebook: chrome-extension://efaidnbmnnnibpcajpcglclefindmkaj/viewer.html?pdfurl=https%3A%2F%2Fucdp.uu.se%2Fdownloads%2Fucdpprio%2Fucdp-prio-acd-211.pdf&clen=292699&chunk=true


After filtering: from 2010-2020, in the African region, we have N=205.


## Unit of analysis:
- event
- maybe safer to look at the news reporting of all the other countries' civil war on the continent


## What does it mean that when news report has positive tone and high volume?
- a little hesitation there: worry about state capacity.
- a way of diffusion: ethnic ties


## Where to find news articles?
- Nexis Unis: https://advance-lexis-com.proxy2.library.illinois.edu/bisacademicresearchhome/?pdmfid=1516831&crid=35473aab-db2c-40f1-8501-d5043ca5e0d8&ecomp=xb3nk&prid=8d2358d0-48d4-4a74-92bc-1712791298da
- Access World Newsbank: https://infoweb-newsbank-com.proxy2.library.illinois.edu/apps/news/browse-multi?p=AWNB&action=browse

**Newsbank contains much more African local news than Nexis Unis. However, news in South Africa and Kenya are over-represented.**


## Example
Keyword: Congo Civil War
Date range: 3/18/2013 - 4/18/2013
Location: Africa

Newsbanks's results: South Africa (29), Kenya (5), Zimbabwe (3), Uganda (2). Notice there is no Congo's news article here! I checked Congo's collection starts later than 2013. 

Then I identified "Le Potentiel" is the leading daily newspaper in DR Congo. No news about the civil war in 2013. Only "La course à l'OIF - L'économie est au cÅ“ur des préoccupations des Etats [analysis]" that show up in both Nexis Unis and Newsbank. 

On Nexis Unis, if I search the territory's name "Katanga" on Nexis Unis withiin the newspaper "Le Potentiel," 78 results show up. If I search "Katanga AND guerre," 17 results -- much better. Then we need to use google translation.

**Takeway**: Lanauge barrier is a thing -- we need to modify our keywords search. Nexis Unis has more complete collection, but we need to identify the leading journals of each country. Newsbank will return more local African news if we search the key terms, but the collection is not complete. 


## Meeting with Alyssa:
UCDP Charts: https://ucdp.uu.se/downloads/charts/

Foreign Broadcast Information Service (FBIS): https://www.library.illinois.edu/hpnl/blog/fbis/

Summary of World Broadcasts: https://clinecenter.illinois.edu/project/data-science/global-news-index (can be accessed via UIUC library??)

## Next steps:

Back to the original plan. Use newspaper reports as pilot data.

## Information about African countries!
Ibrahim Index of African Governance: https://mo.ibrahim.foundation/iiag
