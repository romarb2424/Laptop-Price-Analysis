# Formula Map

## IF / AND / OR

### PriceBand
```excel
=IF(H3<500,"Budget",IF(AND(H3>=500,H3<1000),"Mid-Range",IF(AND(H3>=1000,H3<1500),"Premium",IF(AND(H3>=1500,H3<2500),"Upper Premium","Ultra Premium"))))
```

### Display feature
```excel
=IF(OR(L3="Yes",M3="Yes",N3="Yes"),"Enhanced Display","Standard Display")
```

## VLOOKUP

```excel
=IFERROR(VLOOKUP(I6,Formula_Analysis!$H$2:$I$20,2,FALSE),"N/A")
```

## AVERAGEIF

```excel
=AVERAGEIF(Clean_Data!$AB$2:$AB$1276,D4,Clean_Data!$H$2:$H$1276)
```

## Additional syllabus practice

IF, AND, OR, VLOOKUP, LEFT, RIGHT, MID, CONCATENATE, DATE, TODAY, NOW, DAY, MONTH, YEAR, YEARFRAC, WEEKDAY, TEXT, EDATE, IFERROR, SUMIFS, COUNTIFS, AVERAGEIFS, RANK.EQ, PERCENTILE.INC and CORREL.
