# Examination Crib Sheets

This repository contains, among other things, my personal collection of
double-sided A4 crib sheets intended for use in Mathematics examinations at The
University of York. If you just want the sheets and don't care about any of the
technicalities, go straight to
<https://www-users.york.ac.uk/~od641/exam-crib-sheets> and enjoy! Otherwise,
continue reading.

## Index of Sheets

 * Year 1: Calculus [*In Progress*, Exam: 25th May, 13:30--16:30, F/CENHL]
 * Year 1: Algebra [*In Progress*, Exam: 2nd June, 13:30--16:00, F/CENHL]

## Things to Know

These documents are intended to pack as much information as possible onto two
sides of A4, in line with the Departmental regulations on the use of crib sheets
in examinations. Thus, they may, from time to time, break standard typographical
practice in favour of practicality.

Should you wish to use these sheets for your own exploits, you ought to know
three things:

* The resultant PDFs are not tracked in version control. Therefore, you will
  have to either:

    1. download and compile the documents on your own machine; or

    2. use the ones that I have compiled and made available on-line.

  Option (i) is not particularly difficult, and they don't require any exotic
  packages that aren't on CTAN and included in every modern TeX Live
  distribution; a single invocation of `latexmk -pdf` in the respective
  directory should produce a reasonable PDF document. If you'd prefer (ii), see:
  <https://www-users.york.ac.uk/~od641/exam-crib-sheets>. For convenience and
  accessibility, this link also contains rasters of each PDF for use in other
  applications e.g. MS Office.

* The margins and text are abnormally small, for the reasons described
  above.  Some home printers (old home InkJet series and the like) might
  have trouble printing these documents correctly, so I recommend using a
  high-resolution office laser printer, such as the ones scattered
  throughout The University of York campuses.

* If you have any corrections, comments, or questions concerning the content
  of this repository, please contact me at <od641@york.ac.uk>.

In addition to the crib sheets, I have provided a short commentary on my
predictions for the contents of the upcoming examination for each module. These
guesses are based wholly on the contents of the previous examinations; I do not
have any information that is not equally available to every other student
enrolled on this programme.

## Frequently Asked Questions

**Q**: Am I [OD] allowed to publish these?

**A**: Yes, the sharing of revision resources is certainly allowed. York
students with a Mathematics VLE account can access a Moodle thread which
confirms this:
<https://maths.york.ac.uk/moodle/mod/hsuforum/discuss.php?d=5155>.

**Q**: Under what licence are these materials made available?

**A**: Everything contained within this repository, along with the PDFs
available on my University HTTP instance, is published under the MIT Licence.
Please see the LICENSE file.

**Q**: What is "publish.sh"?

**A**: It is a simple Bash script that compresses PDFs, where necessary, and
uploads them over SSH to my University's web server. The "publishing\_index"
file is a list of all PDF documents that should be subject to this process.
Unless you know my University password and have a recent two-factor
authentication code, neither of these files will be very useful to you ;)

**Q**: Why have I [OD] made these resources public?

**A**: I am sitting these exams, and I would've made all of these materials for
myself anyway, albeit in a private GitHub repository. I see no reason to not
publicise these documents and pieces of information; if you can think of one,
please e-mail me at <od641@york.ac.uk>.

**Q**: Will these be kept up-to-date?

**A**: Once I have sat an examination, I will consider the corresponding crib
sheets and notes as "archived", such that I will not make any updates aside from
fixing obvious errors. I will certainly not delete anything on the basis of it
no longer being personally useful, but nor will I be retrospectively updating
anything to maintain synchronicity with the ever-changing module specifications
and examination formats. If you [an arbitrary future student] would like to
assume that responsibility, feel free to make any changes in a fork and submit a
PR!

