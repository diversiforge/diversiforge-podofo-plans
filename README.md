# diversiforge-podofo-plans
Exactly what it says on the tin: PoDoFo book imposition plans by Diversiforge.

Usage:
```
podofoimpose source.pdf destination.pdf name-of-plan-file.plan lua
```

## 16 page, 4 sheet booklet (2-up)
This will turn a PDF of single pages into a PDF imposed to four pages to a sheet, four sheets to a signature/folio. I typically use this with a 5.5"x8.5" PDF, to print on 11"x8.5" paper, but any PDF that is half the size of your target sheet size should do.

## Tiny book (16-up)
Want a tiny library filled with tiny books? Of course you do. This will cram 32 PDF pages on a single sheet (16 pages to a side). I use this with 11"x8.5" paper and a 2.125"x2.75" PDF, but if you've got bigger (or smaller!) paper, just divide the dimensions by 4 to get your PDF size.

## PDF Splitter
This plan will take a PDF and split it in half vertically. I've used this to make PDF scans of game manuals more usable with an e-reader, but it could also be a useful preprocessing step if you wish to impose a PDF that already has two pages per PDF page.
