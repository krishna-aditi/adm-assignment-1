# INFO7374 Algorithmic Digital Marketing - Assignment 1

## Great Expectations 
Great Expectations is the leading tool for validating, documenting, and profiling your data to maintain quality and improve communication between teams.

## XSV 
XSV is a command line program for indexing, slicing, analyzing, splitting and joining CSV files. Commands should be simple, fast and composable:
- Simple tasks should be easy
- Performance trade offs should be exposed in the CLI interface
- Composition should not come at the expense of performance

### Assignment components
- Run the tutorial for Great Expectations library over the NYC Taxi Data.
- Write 5 expectations for this dataset and create DataDocs
- Based on the profiling, discuss how clean is the dataset
- Using XSV to design and write 5 queries and generate outputs

**Codelabs link:** https://codelabs-preview.appspot.com/?file_id=1TVn5UFq4uGWXg3cnaEMye1MvhW7ZX0uYLI1YDyFTjug#0

**Google Docs source link:** https://docs.google.com/document/d/1TVn5UFq4uGWXg3cnaEMye1MvhW7ZX0uYLI1YDyFTjug/edit#heading=h.mtq1xxsybtxa

### References
1. https://docs.greatexpectations.io/docs/tutorials/getting_started/tutorial_validate_data
2. https://medium.com/hashmapinc/understanding-great-expectations-and-how-to-use-it-7754c78962f4
3. https://github.com/BurntSushi/xsv#installation
4. https://github.com/BurntSushi/xsv/issues/280
5. https://github.com/googlecodelabs/tools/blob/main/FORMAT-GUIDE.md
6. https://gist.github.com/dannguyen/376c69380f99d1eeca7ad6e890f96259

## Project Structure
--------
        great_expectations
        ├── great_expectations.yml
        ├── expectations
        │   ├── ass_1_attempt_2.json
        ├── checkpoints
        │   ├── ass_1_checkpoint_1.yml
        ├── plugins
        │   ├── data_docs_custom_styles.css
        ├── uncommitted
        │   ├── config_variables.yml       
        │   ├── data_docs        
        │   ├── datasource_new.ipynb 
        │   ├── edit_ass_1_attempt_2.ipynb
        │   ├── edit_checkpoint_ass_1_checkpoint_1.ipynb
        │   └── validations           
        └── .gitignore

--------
