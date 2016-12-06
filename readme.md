See <a href="http://versologie.cz/talks/aseees2016/">presentation</a> from <a href="http://aseees.org/convention">ASEEES2016</a> for details.

#### Datasets

Czech dataset comes from the <a href="versologie.cz">Corpus of Czech Verse</a>, English & French ones are based on those provided by <a href="https://github.com/sravanareddy/rhymedata">Sravana Reddy</a>

#### Schema

```xml
<data>
  <poem id="TEXT" author="TEXT" period="INT">
    <line id="INT" finToken="TEXT" finSampa="TEXT" rhymeScheme="TEXT" stanzaId="INT"/>
    ...
  </poem>
  ...
</data>
```

#### Dependencies

Data::Dumper  
File::Basename  
XML::Simple  
Deep::Encode  