# whatsapp-archive

Format your exported WhatsApp conversation in HTML.

Use the [Saving your chat history][saving] instructions to export your chat
history. You'll get an email with a .txt file. Save it on disk, and then run
this script.

Requirements (on Debian):

   * `python3-dateutil`
   * `python3-jinja2`
   * `python3-parameterized`

On Linux, run this in shell. On Windows, run this in cmd.

    ./whatsapp_archive.py -i your_file.txt -o output.html

Coding style follows the [Google Python Style Guide][pystyle].

Interesting forks of this repository:

- https://github.com/shrick/comm-history supports email as well.
- https://github.com/dsadinoff/whatsapp-archive handles bidirectional text
  (see Issue #5).
- https://github.com/djax666/whatsapp-archive contains good instructions
  about how to make an export.

[saving]: https://faq.whatsapp.com/en/android/23756533/?category=5245251
[pystyle]: https://google.github.io/styleguide/pyguide.html
