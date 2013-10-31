Hello! Please note that this is the transcript of what I'm going to do as I try a live demo for Monster Mashup. The site where you can access a walkthrough is here:  [http://michellehudson.github.io/monster_mashup/](http://michellehudson.github.io/monster_mashup/)

### Download OpenRefine. http://openrefine.org/

### Find data:
* Marc Carlson's tables on Historical Witches: http://www.personal.utulsa.edu/~marc-carlson/carl4.html

### Import tables into Excel:

1. Launch Excel
2. Go to "Data" tab
3. Select to "add data from web"
4. Navigate to the table of interest: http://www.personal.utulsa.edu/~marc-carlson/witchtrial/na.html
5. Click the arrow next to the table
6. Do a checkthrough to make sure it looks okay
7. Save the file somewhere you can find it
8. Done!

### Ingest & explore data:

1. Launch OpenRefine
2. Create a new project by uploading the Excel file you just created
3. Check the options for anything of note (does your first row contain headers?)
4. Start faceting to see patterns:
     *Dates* -- mostly years, but some years and months where available
     *Names* -- some people were tried more than once
     *Numbers* -- in some cases, my table defines that several people were tried at once
     *Places* -- which places have the most records
     *New Haven* -- export a table of the New Haven county witch trials to HTML

### Clean & merge data:

Now that you know facets, you can use facets and clustering to fix things:
     *Sex* -- does this correspond? Does anything need to be flagged? Flag it.
     *Places* -- Lots of places have * or ? -- but for my purpose, let's say that doesn't matter. I can merge all these places, as well as any places that are just misspelled or have a typo.
     
### Split columns:

If you have one column of information, you can turn it into several columns. For example, separate "NEng" from "State" from "City" where available in your *Place* column.

You can also find the items you've flagged as a facet to make going back to fix them easier.

You can undo or redo each step as neccessary.

For more, watch the official tutorial videos! This one on [Reconciliation](http://www.youtube.com/watch?v=5tsyz3ibYzk) is really good. Refine can do a lot more than I’ve shown here. There’s also a great [OpenRefine wiki on GitHub](https://github.com/OpenRefine/OpenRefine/wiki/External-Resources).
