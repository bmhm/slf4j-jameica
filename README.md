[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![Build Status](https://travis-ci.org/bmhm/slf4j-jameica?branch=master)](https://travis-ci.org/bmhm/slf4j-jameica) [![Codacy Badge](https://api.codacy.com/project/badge/Grade/4f0a36fd479b44a590f0a8bc9e796c68)](https://www.codacy.com/app/bmarwell/slf4j-jameica?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bmhm/slf4j-jameica&amp;utm_campaign=Badge_Grade) [![Codacy Badge](https://api.codacy.com/project/badge/Coverage/4f0a36fd479b44a590f0a8bc9e796c68)](https://www.codacy.com/app/bmarwell/slf4j-jameica?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=bmhm/slf4j-jameica&amp;utm_campaign=Badge_Coverage)


# slf4j-jameica

Log Adapter for SLF4j-Users, who want to see their logging output (using the slf4j api) in jameica.

## Installation

Add my repository to Jameica.
Instructions at [bmhm.github.io](https://bmhm.github.io/).

## Requirements
* Jameica 2.6+
* Java 8 or later.

## Dependencies

* slf4j 1.8 (at runtime, shipped)
  I use the new JDK9-compatible ServiceProvider implementation.
  As you might have known, slf4j prior to version 1.8
  does not support Java 9.
* jameica-core (provided, i.e. at compile time).
  This artifact is generated from the jameica source code.
  Used for the AbstractPlugin class.
* jameica-util
  This artifact is also generated.
  Used for the Logger class.


