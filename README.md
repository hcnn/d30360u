# d30360u
* Date difference in years according to the **30/360 ISDA** daycount method
* Synonyms: 30/360 ISDA, 30U/360, 30/360 US, 30/360 Bond Basis, 30/360 U.S. Municipal, American Basic Rule


## ISO 20022 -- A001

    "Method whereby interest is calculated based on a 30-day month and a 360-day year. Accrued interest to a value date on the last day of a month shall be the same as to the 30th calendar day of the same month, except for February, and provided that the interest period started on a 30th or a 31st. This means that a 31st is assumed to be a 30th if the period started on a 30th or a 31st and the 28 Feb (or 29 Feb for a leap year) is assumed to be a 28th (or 29th). It is the most commonly used 30/360 method for US straight and convertible bonds."

[link](https://www.iso20022.org/15022/uhb/mt565-16-field-22f.htm)


### Installation
```
clib install hcnn/d30360u
```

Or add to your `package.json` and run `clib install`

```
{ ...
    "dependencies": {
        "hcnn/d30360u": "0.1.0"
        ...
```

### Test and Demo
Download, compile, and run [test.c](https://github.com/hcnn/d30360u/blob/master/test.c) and [demo.c](https://github.com/hcnn/d30360u/blob/master/demo.c)

```
git clone git@github.com:hcnn/d30360u.git
cd d30360u
make deps
make validate
make showcase
```
