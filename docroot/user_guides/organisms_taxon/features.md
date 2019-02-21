# Features Tab

## Overview
The Features Tab provides a table of all the annotated genomic features (gene, CDS, mRNA, etc.) corresponding to the set of genomes in the selected Taxon View level or in the user-defined Genome Group.  From this page, features can be sorted, filtered, collected into groups, and downloaded. 

### See also
  * [Genome Annotations](../organisms_taxon/genome_annotations.html)
  * [Genome Page Overview](../organisms_genome/overview.html)
  * [Multiple Sequence Alignment Viewer](../other/msa_viewer.html)

## Accessing the Features Table on the PATRIC Website
Clicking the Features Tab in a Taxon View displays the Features Table (shown below), listing all the annotated genomic features corresponding to the set of genomes in the selected taxon level.

![Features Table](../images/features_tab.png)

The genomic features include those called by the PATRIC [(RASTtk)](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC4322359/) annotation service as well as the original annotations (typically from RefSeq), if availalble. 

### Features Table Tools
Within this table you may do the following:

* **Download** the entire contents of the table in text, CSV, or Excel format by clicking the Download button above the table on the left side.

* **Rearrange and narrow** the list of sequences in the table via sorting (using column headers), keywords (using the Keyword box), and filtering (using the Filters tool).

### Filter Tool

As with all tables in PATRIC, the Filters tool is available to narrow the display of the items in the table, show below:
  
![Features Filter Panel](../images/features_filter_panel.png)

Clicking on the Filters button at the top right of the table opens the Filter Panel above the table, displaying column names from the table and values for those columns with counts of occurence.  Clicking on the filter values narrows the features displayed in the table to those matching the chosen filter values.  Clicking the Hide button closes the Filter Panel. More details are available in the [Filter Tool](../other/filter_tool.html) user guide.

### Action buttons

After selecting one or more of the features by clicking the checkbox beside the Genome Name in the table, a set of options becomes available in the vertical green Action Bar on the right side of the table.  These include

* **Hide/Show:** Toggles (hides) the right-hand side Details Pane.
* **Download:**  Downloads the selected items (rows).
* **Copy:** Copies the selected items to the clipboard.
* **Feature:** Loads the Feature Page for the selected feature. *Available only if a single feature is selected.*
* **Features:** Loads the Features Table for the selected features. *Available only if multiple features are selected.*
* **Genome:** Loads the Genome View Overview page corresponding to the selected feature.  *Available only if a single feature is selected.*
* **Genomes:** Loads the Genomes Table, listing the genomes that correspond to the selected features. *Available only if multiple features are selected.*
* **FASTA:** Provides the FASTA DNA or protein sequence for the selected feature(s).
* **ID Map:** Provides the option to map the selected feature(s) to multiple other idenfiers, such as RefSeq and UniProt.
* **MSA:** Launches the PATRIC Multiple Sequence Alignment (MSA) tool and aligns the selected features by DNA or protein sequence in an interactive viewer.
* **Pathway:** Loads the Pathway Summary Table containing a list of all the pathways in PATRIC in which the selected features are found.
* **Group:** Opens a pop-up window to enable adding the selected sequences to an existing or new group in the private workspace.

More details are available in the [Action Buttons](../other/action_buttons.html) user guide.
