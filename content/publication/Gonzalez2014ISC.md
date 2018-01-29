---
DOI: 10.1007/978-3-319-13257-0_35
abstract: "Current efforts to increase the security of the boot sequence for mobile\
  \ devices fall into two main categories: (i) secure boot: where each stage in the\
  \ boot sequence is evaluated, aborting the boot process if a non expected component\
  \ attempts to be loaded; and (ii) trusted boot: where a log is maintained with the\
  \ components that have been loaded in the boot process for later audit. The first\
  \ approach is often criticized for locking down devices, thus reducing users\u2019\
  \ freedom to choose software. The second lacks the mechanisms to enforce any form\
  \ of run-time verification. In this paper, we present the architecture for a two-phase\
  \ boot verification that addresses these shortcomings. In the first phase, at boot-time\
  \ the integrity of the bootloader and OS images are verified and logged; in the\
  \ second phase, at run-time applications can check the boot traces and verify that\
  \ the running software satisfies their security requirements. This is a first step\
  \ towards supporting usage control primitives for running applications. Our approach\
  \ relies on off-the-shelf secure hardware that is available in a multitude of mobile\
  \ devices: ARM TrustZone as a Trusted Execution Environment, and Secure Element\
  \ as a tamper-resistant unit."
authors: ["Javier Gonz\xE1lez", "Michael H\xF6lzl", Peter Riedl, Philippe Bonnet,
  "Ren\xE9 Mayrhofer"]
date: '2014-10-01'
id: Gonzalez2014ISC
issued:
- {month: 10, year: 2014}
page: 542-554
publication: Proc. Information Security Conference 2014 (ISC)
publication_types: [1]
publisher: Springer
title: A Practical Hardware-Assisted Approach to Customize Trusted Boot for Mobile
  Devices
url_custom:
- {name: bibtex, url: files/bibs/Gonzalez2014ISC.bib}
- {name: DOI, url: 'https://doi.org/10.1007/978-3-319-13257-0_35'}
url_pdf: files/pdfs/Gonzalez2014ISC
volume: '8783'
---
