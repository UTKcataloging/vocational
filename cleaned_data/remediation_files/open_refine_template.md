# Open Refine Template for Anna Catherine Wiley Sketches


## Template

#### Prefix

```
<?xml version="1.0" encoding="UTF-8"?>
<modsCollection xmlns="http://www.loc.gov/mods/v3" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:xlink="http://www.w3.org/1999/xlink" xsi:schemaLocation="http://www.loc.gov/mods/v3 http://www.loc.gov/standards/mods/v3/mods-3-5.xsd">
```
####Body

```
<mods>
<identifier type="local">{{cells["identifier"].value}}</identifier>
<titleInfo><title>{{cells['title'].value}}</title></titleInfo>
<abstract>Periodical published twice a month by the disabled ex-service men in training at the University of Tennessee</abstract>
<name type="corporate" valueURI="http://id.loc.gov/authorities/names/n80003887">
<namePart>University of Tennessee (Knoxville campus)</namePart>
<role>
<roleTerm authority="marcrelator" valueURI="http://id.loc.gov/vocabulary/relators/cre">Creator</roleTerm>
</role>
</name>
<physicalDescription><form authority="aat" valueURI="http://vocab.getty.edu/aat/300026657">periodicals</form></physicalDescription>
<originInfo><dateIssued>{{cells['date_text'].value}}</dateIssued><dateIssued encoding="edtf">{{cells['date_edtf'].value}}</dateIssued><place><placeTerm valueURI="http://id.loc.gov/authorities/names/n79109786">Knoxville (Tenn.)</placeTerm></place></originInfo>
<subject authority="lcsh" valueURI="http://id.loc.gov/authorities/subjects/sh2009123449"><topic>Disabled veterans-Vocational rehabilitation-United States</topic></subject>
<subject authority="lcsh" valueURI="http://id.loc.gov/authorities/subjects/sh2008113196"><topic>Veterans-Education-United States</topic></subject>
<typeOfResource>text</typeOfResource>
<relatedItem displayLabel="Project" type="host"><titleInfo><title>Vocational Voice</title></titleInfo></relatedItem>
<location><physicalLocation valueURI="http://id.loc.gov/authorities/names/no2014027633">University of Tennessee, Knoxville. Special Collections</physicalLocation></location>
<language><languageTerm type="text" authority="iso639-2b">English</languageTerm></language>
<recordInfo><recordContentSource valueURI="http://id.loc.gov/authorities/names/n87808088">University of Tennessee, Knoxville. Libraries</recordContentSource><languageOfCataloging><languageTerm type="text" authority="iso639-2b">English</languageTerm></languageOfCataloging><recordOrigin>
Created and edited in general conformance to MODS Guidelines (Version 3.5).
</recordOrigin></recordInfo>
<accessCondition type="use and reproduction" xlink:href="http://rightsstatements.org/vocab/NoC-US/1.0/">No Copyright - United States</accessCondition>
</mods>

```

#### Suffix

```
</modsCollection>
```