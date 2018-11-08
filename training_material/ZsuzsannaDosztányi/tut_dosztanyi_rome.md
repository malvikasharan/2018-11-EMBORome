Prediction of protein disorder and disordered binding regions {#prediction-of-protein-disorder-and-disordered-binding-regions .western style="margin-top: 0in; margin-bottom: 0in; page-break-before: always"}
=============================================================

\

*Zsuzsanna Dosztányi*

Exercise 1 {#exercise-1 .western}
----------

**DISPROT database and analyzing <span
style="font-variant: normal"><span style="letter-spacing: normal"><span
style="font-style: normal">Cyclin-dependent kinase inhibitor
1B</span></span></span><span style="font-variant: normal"><span
style="letter-spacing: normal"><span style="font-style: normal">
</span></span></span><span style="font-variant: normal"><span
style="letter-spacing: normal"><span
style="font-style: normal">(p</span></span></span>27)**

Find the uniprot entry: **P46527**. The Disprot database is linked to
Uniprot.

Find the DisProt link on the webpage.

What is the Disrprot ID corresponding to this protein?

(You could have search for this protein directly through the DisProt
database using the search box)

\

Go to the section <span style="font-variant: normal"><span
style="letter-spacing: normal"><span
style="font-style: normal">**Disorder Region
Details**</span></span></span><span style="font-variant: normal"><span
style="letter-spacing: normal"><span
style="font-style: normal">**.**</span></span></span>

<span style="font-variant: normal"><span
style="letter-spacing: normal"><span style="font-style: normal"> ****
</span></span></span><span style="font-variant: normal"><span
style="letter-spacing: normal"><span style="font-style: normal"><span
style="font-weight: normal">How many regions are annotated as
disordered?</span></span></span></span>

<span style="font-variant: normal"><span
style="letter-spacing: normal"><span style="font-style: normal"><span
style="font-weight: normal">E</span></span></span></span><span
style="font-variant: normal"><span style="letter-spacing: normal"><span
style="font-style: normal"><span style="font-weight: normal">xamine the
Region Evidence for each regions.</span></span></span></span>

What type of methods were used to show the disordered nature of the
regions?

Which are the corresponding publication? (PMID?)

Can you confidently say that this protein is disordered?

If you only had the first experiment (Circular Dichroism (Cd)
Spectroscopy, Far-Uv ), would it be the same?

\

Check out the functional annotation: (**Functional Annotation**
**section**)

What are the potential functions of the disordered regions?

Are any of these regions involved in disorder-to-order transition?

Any of the regions correspond to linkers/spacers?

Check out additional information. Go to **Disorder Overview**
**section.**

Which regions has a corresponding PFAM annotation? Does it overlap with
a disorder annotation? Is there a contradiction?

[]() Exercise 2 {#exercise-2 .western style="margin-top: 0in; margin-bottom: 0in"}
---------------

### []()Disorder prediction methods {#disorder-prediction-methods .western}

1.  

The input can be:

-   -   -   

> Please note, some methods are sensitive to line breaks. Minimum and
> maximum length of sequence

Some disorder prediction methods:

-   -   -   -   

Results are available for DISOPRED3 here:

<http://bioinf.cs.ucl.ac.uk/psipred/result/33e7bc44-e1b3-11e8-9dd9-00163e110593>

\

\

-   

\
\

Do the predictions agree with the experimental characterization of
disorder?

\
\

Exercise 3 {#exercise-3 .western style="margin-top: 0in; margin-bottom: 0in"}
----------

**IUPred2 – Potential function of disordered regions**

Go to IUPred2a website (
[http://iupred2a.elte.hu](http://iupred2a.elte.hu/){.western})

Predict the disorder and disordered binding regions for protein for
protein <span style="font-style: normal">**P47047**</span>***.*** The
server can take a Uniprot ID or accession as well a sequence. Run the
predictions with default option.

You can turn on and off ANCHOR or IUPred visualization on the plot.

Which regions are predicted disordered? Depending on the location of
domains, predicted disordered binding regions and known disordered
binding regions, can you guess the potential functions of the N-terminal
region and the disordered region between the two domains?

\

\
 {#section .western style="margin-top: 0in; margin-bottom: 0in"}
-

\
\

Exercise 4 {#exercise-4 .western align="left" style="margin-top: 0in; margin-bottom: 0in; line-height: 150%"}
----------

**MobiDB Database – using direct and indirect data to characterize
disorder-to-order**

Find the p27 in the MobiDB database. (It is crosslinked from the DisProt
database, or use the link:

http://mobidb.bio.unipd.it/P46527)

\

Go the ***Predictions*** section. Here you can find the results of
additional prediction methods.

Check the results of MobiDB-lite, which is a conservative (tries to
avoid overprediction of disorder) consensus prediction method.

\

Go to the ***Curated*** section.

Which regions are disordered based on the consensus? Is there a region
in conflict?

In which other databases can you find evidence for the disorder status
of this protein?

Which evidence points to that this regions is ordered, and which points
to order?

\

Go to the ***Indirect Evidence*** section.

MobiDB automatically collects complexes that contain so-called Linear
Interacting Peptides (LIPS-- regions that form more contacts with their
partner than within themselves).

Click on LIPs

Which regions are involved in linear peptide interactions?

Which are the corresponding PDB IDs?

\

Go to the ****** ***Interactions*** section.

Check the interactions sites with known partners.

\
 {#section-1 .western style="margin-top: 0in; margin-bottom: 0in"}
-

Exercise 5 {#exercise-5 .western style="margin-top: 0in; margin-bottom: 0in"}
----------

\

**DIBS database (courtesy of Dr. Bálint Mészáros)**

The exercise focuses on the interactions of the disordered human H3.1
histone protein.

\

The DIBS database (<http://dibs.enzim.ttk.mta.hu/>) contains
interactions that are formed with ordered protein partners:

\

Find and open two interactions in DIBS with IDs **DI1000022** and
**DI2000021**.

Which regions of H3.1 are present in the two interactions? Do these
regions overlap? (use the ‘Structure Summary’ menu item, and focus only
on positions that are marked as having solved structure in the
structural feature viewer).

What are the partners in the two cases?

Are the two bound H3.1 conformations different? Use the structure viewer
on the top right corner of each page.

Are there differences between the two interactions in terms of K~d~?

What kind of post-translational modifications (eg.
phosphorylation/methylation/acetylation/etc.) are present on histone
H3.1 in the two interactions?

\

(Optional)

Different interactions that involve the same disordered segment of a
protein but different partners tend to compete with one another. In the
case of simple competition, the interaction with the smaller K~d~ is
favored. If the difference between K~d~s is large, the higher K~d~
interaction would normally never occur. What other factors can be at
play in this specific case, so that both interactions can form inside
the cell?

\

\

\

