# BASS:ON Website

I've ([@itisrazza]) made this website for our BASS:ON homepage.

I've taken care so it's maintainable as much as possible for the GitHub website. If something doesn't work, get in touch.

## Adding an Event

* Create a new event in `_events/%year%-%name%.md` copying [this template](_events/example-rave.md).
* Add a background graphic in [`static/banners/%year%-%name%.jpg`](static/banners).

## Adding an Artist

* Add the artists' details to [`_data/artists.yml`](_data/artists.yml) (look for `example:`).
* Add an avatar pic to [`static/artists/%id%.jpg`](static/artists).

## Preview your changes

After your commit, the changes should be visible on https://bass-on-draft.razza.io.

You can manually force a publish by going to [this page](https://github.com/itisrazza/bass.on/actions/workflows/jekyll.yml), click Run Workflow, then in the pulldown, click Run Workflow.

---

&copy; 2022 BASS:ON

[@itisrazza]: https://github.com/itisrazza
