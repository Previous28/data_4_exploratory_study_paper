Dataset for our exploratory study paper《Method Comment vs. Inline Comment: An Exploratory Study on the Automatic Comment Generation》

The dataset includes four JSON files, they are:

- method.json
- inline.json

- method_wo_tmpl.json
- inline_wo_tmpl.json

**method.json** and **inline.json** are the original datasets. While **method_wo_tmpl.json** and **inline_wo_tmpl.json** are datasets after removing the template comments.

Each line in these JSON files is a data sample, which is represented by a JSON object. The field information of the JSON object is:

- For **method.json** and **inline.json**:
  - *code*: string
  - *origin_cmt*: original comment without any processing, string
- For **method_wo_tmpl.json** and **inline_wo_tmpl.json**:
  - *code*: string
  - *origin_cmt*: original comment without any processing, string
  - *cmt*: extracted from the first sentence of the original comment, used for code comment generation experiment, string

