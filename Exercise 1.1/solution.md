v2 is missing these two lines, which are at ln 454-454 of v1

```
<xs:element name="BkPtyId" type="Max35Text" minOccurs="0" maxOccurs="1"/>
<xs:element name="TaxIdNb" type="Max35Text" minOccurs="0" maxOccurs="1"/>
```

v1 has "mixed" line endings, whereas v2 has windows line endings

![Screenshot solution (WinMerge)](solution%20(WinMerge).png "Screenshot solution (WinMerge)")