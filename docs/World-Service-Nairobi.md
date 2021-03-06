# BBC Connected Studio: World Service - Nairobi

The following information is intended for attendees of the [BBC Connected Studio: World Service](http://www.bbc.co.uk/corporate2/connectedstudio/events) event in Nairobi.

## Categories for this event

There are 5 categories for entries for this event:

* ####Best hack using ChatApp/Social Media
* ####Best hack using SMS and/or USSD
* ####Most cost effective solution/offline functionality
* ####Best for community building/sharing/interaction
* ####Surprise us!

## BBC Content APIs

### API Key

To use the BBC APIs you will need an API Key, which we have created for this event:

>    ~~`o4t8FNmk02fngjizZPAzZNPt7oy2Adup`~~ 

You should replace the text `{{apikey}}` in the examples with this key.

**UPDATE: The API key for this event has now been retired.**

### [Juicer API Documentation](Juicer.html)

*Please note that content from the Juicer is suitable for use only for Research and Development purposes.*

The Juicer is tool for automatic entity extraction and artchiving from BBC News Labs.

You can use it fetch the latest news as well running queries for news coverage from the BBC and other news organisations.

[Check out the documentation for the Juicer API](Juicer.html) to get started.

#### Regional Sources

If you specify 'NewsWeb' as the 'Product' you will get BBC News content in English and a range of other languages.

In addition to being able to specify the 'NewsWeb' as the 'Product' to get BBC News content, you can also search content from other sources.

For example, you can pass any of these options to the 'product[]' parameter:

* KenyaBroadcastingCorporation
* NigerDeltaStandard
* NationalElectionCommissionSudan
* DailyNewsEgypt
* TechMoran 

##### Example

```
http://data.bbc.co.uk/bbcrd-juicer/articles.json?product[]=DailyNewsEgypt&product[]=KenyaBroadcastingCorporation&product[]=TechMoran&product[]=NigerDeltaStandard&product[]=NationalElectionCommissionSudan&content_format[]=TextualFormat&recent_first=yes&apikey={{apikey}}
```

### [Content Store API](CANDY.html) 

The BBC Content Store API (aka CANDY) provides an interface to BBC News content with structured metadata.

CANDY stands for "CPS and Dynamic", it integrates the Content Production System (CPS) with the Dynamic Semantic Publishing system (DSP).

The Content Store API is a production platform, used internally by the BBC on the BBC website and in BBC mobile apps.

In addition to English, the Content Store includes articles written in several languages.

[Check out the documentation for the Content Store API](CANDY.html) to get started.

### Sample Video & Audio Content

You can get images by using the Juicer and Content APIs (which return images associated with articles).

In addtion, we've provided some sample video, shortform video (intended for mobile) and audio content for use during the event.

* Sample video http://media.bbcnewslabs.co.uk/videos/
* Sample short form video http://media.bbcnewslabs.co.uk/shorts/
* Sample audio http://media.bbcnewslabs.co.uk/audio/

## BBC Africa on Social Media

* Facebook, "BBC Africa News" https://www.facebook.com/bbcafrica
* Twitter https://twitter.com/BBCAfrica  and #BBCGoFigure
* Google+ https://plus.google.com/+BBCAfrica/posts 
* YouTube https://www.youtube.com/user/bbcafrica 
* SoundCloud https://soundcloud.com/bbcafrica 
* WhatsApp (Ebola:) +447702348651 - Send a subscribe request via WhatsApp.

     Alternatively we email numbers of the people/teams who want to access to Trushar who can add them. Requests through WhatsApp may be delayed. Subscribe by searching for the ID **BBC News** or by scanning this QR code:
     <br>
     <img src="http://qr-official.line.me/sid/L/bbcnews.png" alt="QR code" class="img-responsive" style="max-height: 300px !important;" />

## BBC Programmes

* African programmes http://www.bbc.co.uk/programmes/p0107lkh 
* Focus On Africa http://www.bbc.co.uk/programmes/p00gbjvb 
* News Summaries http://www.bbc.co.uk/programmes/p002vsn1/episodes/player 
* Podcast - AfricaToday http://www.bbc.co.uk/podcasts/series/africa 

## BBC Learning English resources

* http://www.bbc.co.uk/learningenglish/ 
* https://www.youtube.com/user/bbclearningenglish 

## Other resources

You can find some links to platforms and services that might come in useful below.

These services are not endorsed by the BBC and you do not need to use them, you are free to use other platforms, services and frameworks.

#### Messaging clients and content platforms

* [WeChat](http://www.wechat.com)
* [WeChat Builder](http://www.wechatbuilder.com)
* [Mxit](http://get.mxit.com) (see also their [Developer Documentation](https://dev.mxit.com/docs))
* [Vumi](http://vumi.org)
* [Mara messenger](https://messenger.mara.com)

#### SMS platforms

* [FrontlineSMS](http://www.frontlinesms.com)
* [RapidPro](https://www.rapidpro.io)

#### Other resources

* [BBC News Labs Bootstrap](http://bootstrap.bbcnewslabs.co.uk)
* [BBC GEL](http://www.bbc.co.uk/gel)
* [JSONProxy](https://jsonp.nodejitsu.com) (You may find this useful to use for prototyping with the BBC Content API)
* [Kenya Open Data](https://www.opendata.go.ke)
* [BRCK](http://brck.com)
 