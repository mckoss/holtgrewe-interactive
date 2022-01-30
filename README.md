# Holtgrewe Interactive

Project to modernize the Holtgrewe Interactive exhibit from the Museum of
Flight.

The WWI Holtgrewe model database interactive is displayed in the
Personal Courage Wing, yet it using obsolete technology that is
no longer widely supported.

I have also collected the WWII artifacts here for a follow on project.

## Project Goals

- Collect original media files and content from the Flash-based
  interactive exhibit.
- Verify complete via running the [Adobe Flash
  Projector](https://fpdownload.macromedia.com/pub/flashplayer/updaters/32/flashplayer_32_sa.exe)
- Decompile the elements from the Flash file(s) to extract all the
  original media that was used (e.g., using
  [JEPXS Flash decompiler](https://github.com/jindrapetrik/jpexs-decompiler)).
- Build a modern version of the application in HTML/CSS/Javascript that
  can be run on modern browsers (desktop, mobile, or kiosk modes).

## Resources

List of files are available on the [Wayback
Machine](https://web.archive.org/web/*/http://www.museumofflight.org/files/video/HoltgreweInteractive_Web/*)

Museum of Flight website is still hosting the original content - but just not
linking to it:

https://www.museumofflight.org/files/video/HoltgreweInteractive_Web

See the [archive](/archive) directory in this repository for a collection
of all the data and assets associated with these applications.

## Design

Having run the emulator for the WWII app, I've authored a
[design-document](/docs/wwi-design.md) that lays our the pages and workings
of the application.


