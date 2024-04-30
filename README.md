# ad-text-understanding
Includeing Qwen-72B ad-text-understanding, GTE/M3E/UNIEM training checkpoints. Application of traditional machine learning algorithms in advertising industry segmentation.

Over the past 2 weeks, we have been relentlessly plagued by bugs and exhaustion. 
To avoid these annoyances, we have documented them in this file and are working to overcome them.

BUG 1: Spaces in queries cause instability in the Redius category.
BUG 2: Appending columns in different conditional loops leads to misalignment in the eph category.
BUG 3: Some queries extracted from JD fail to insert into the cache table.
BUG 4: Delimiters exist in standard recall units.
BUG 5: Unnecessary instructions result in weak and overly general outcomes for Qwen-72B.
To address these issues, we have decided to store all data in a JSON file using a key-value pair format and reevaluate our understanding of them.
