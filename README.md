# Basta!

A bundle of phing build files to add basic GUI controls for
Buster.JS and PhantomJS to WebStorm/PHPStorm/IntelliJ IDEA.

(NB: WebStorm and PHPStorm have no Apache Ant GUI)

## Requirements
  - phing http://www.phing.info/trac/wiki/Users/Installation
  - phing plugin for WebStorm/IntelliJ IDEA (bundled with PHPStorm)
  - Buster.JS
  - PhantomJS

## IDE configuration:
Select "Add as Phing Build file" in the context menu of all phing/*.xml files.
Optional: In the Phing Build tool window, select "Mark to hide" in the context
menu of all targets.

## Usage
  - run buster.xml to start the test server
  - run headless.xml to attach a headless webkit browser to the server
  - run test.xml as often as you need to
  - when you're done, close the headless and buster processes from the Messages tool window (basta!)
