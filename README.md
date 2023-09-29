#### Demo for bug extension
The bug: css is not loaded by chrome side panel extension

To recreate: 
- clone git@github.com:yigalirani/cssbug.git
- using chrome, goto chrome://extensions/
- click 'load unpacked'
- select the directory to which h you clone the repo
- open the extension by clicking the side bar and selecting  cssdemo
- expected result: the panel display should consist of two line, one red and one red
- actual result: the line with text 'external css - background should be red' is not read
