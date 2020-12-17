#### Comparing as text

v2 has an additional line at ln 700, which is missing in v1

```
</xs:complexType>
```

v1 has "mixed" line endings, whereas v2 has windows line endings

![Screenshot solution text (WinMerge)](solution%20text%20(WinMerge).png "Screenshot solution text (WinMerge)")

#### Comparing as xml

This additional line in v2 makes the xml invalid

![v2 xml invalid](v2%20xml%20invalid.png)("v2 xml invalid")

![Screenshot solution xml (WinMerge)](solution%20xml%20(WinMerge).png "Screenshot solution xml (WinMerge)")