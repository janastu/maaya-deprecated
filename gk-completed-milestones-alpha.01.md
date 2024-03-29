# Maaya
as in Illusion

is a frontend tool to create interactive oral history presentations

## Tasks
### Milestone 1 - Prepare transcript (status: completed)
We already have the transcripts for [Oral history inteview](http://team.servelots.com/my/pradeep/chaluvaraju/HampiGirijaKalyanaStorybyCraju.mp3) in Kannada and english,
we need the timestamp data, so this phase is about 
copy pasting relevant paragraphs from these docs,
[Kannada text](http://gk.chaha.in/#gk-kannada) and [English translation](https://docs.google.com/document/d/1hKJPsB1KE3sJ4HOM2F3GW5-_Obb4so3vQYm9i3K1ElU/edit)

1. create transcript using [transcript tool](http://transcribe.test.openrun.net/)
2. export transcript in text format
3. convert text to JSON as in the structure 
```
{
	"start": "timevalue",
	"kan": "kannada text",
	"eng": "english translation"
}
```



### Milestone 2 - Create a JSONLD (status: completed)
This phase will be about the data structure for the whole presentation.

1. Review links index from this [doc](https://docs.google.com/document/d/1SpQhOALzCGvAGutavnIZ5F4UnwEK0Ix60miHr6ux-V4/edit)
2. collect image, videos, text and other relevant resource 
3. JSONLD structure from this [doc](https://docs.google.com/document/d/1EqombmFP43xpcXPqHfmafJctsns5FcXfQdYK_RKUR9w/edit)

### Milestone 3 - OH App integration (status:completed)
1. Use this data with the [OH app](https://github.com/janastu/ncbs-oral-history )
2. Design layout and UX