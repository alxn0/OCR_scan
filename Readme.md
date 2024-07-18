# Building an OCR scan pipeline with my DS-720D

Objective:

Create a CLI pipeline to scan document to PDF OCR with options for
dimension (A4, letters, etc.) and tesseract language.

Add metadata to PDF

## Done
- Got the scanner running with the Brother brscan5 drivers
- OCRed a tiff at 300dpi 
- Got the A4 dimension working with xsane previer mode

## Todo
- Tried to find the backed command with scanimage
    - Can Xsane started from the CLI will display the command?
    - Maybe on the Brother
      [FAQ](https://support.brother.com/g/b/faqlist.aspx?c=us&lang=en&prod=ds740d_all&ftype3=100258)
    - From the [man](http://www.sane-project.org/man/scanimage.1.html)
    - Brother seems to prefer Xsane as a way to modify configurations,
      see this
      [FAQ](https://support.brother.com/g/b/faqend.aspx?c=us&lang=en&prod=ds740d_all&ftype3=100258&faqid=faq00100711_000)

- Add PDF-metadata
    - See this post from [stackoverflow](https://askubuntu.com/questions/27381/how-to-edit-pdf-metadata-from-command-line)
    - See this medium
      [post](https://medium.com/@drag0s.stanescu/pdf-metadata-and-practical-examples-of-how-to-handle-it-a6954fa2c374)
      for more information on PDFs metadata
