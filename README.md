# columbia-course-parser
A simple script to parse a page of the Columbia Directory of Classes into a useable class, and cross reference it with the CULPA gold and silver nugget rankings

## Example

```
python parser.py http://www.columbia.edu/cu/bulletin/uwb/subj/HUMA/_Fall2018.html
```

will create a courses.txt file in the same directory, which contains a list of all the classes in the given directory page, along with the professor, the section number, the enrollment, and optionally the CULPA nugget status of each professor teaching a section. Just pass an arbitrary directory page to it for a given semester, and it will produce that document.

See the examples folder for more examples.

### Dependencies

This script uses Beautiful Soup (bs4) and the requests module to parse the course directory. To install these, use pip from the command line with

```
pip install bs4 requests
```
