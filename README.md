# YT2Grayjay
Simple Script to convert youtube History to grayjay history


You need python and a takeout of your youtube history.
extract watch.history.json (in this example we use d:\python as our working directory)
adjust path in the script if using a different one.

run it.

upload output.zip to your phone
import "from grayjay export"
skip everything EXCEPT "import stores - yes, import history - yes"


Warning if you have a lot of history set your screentime timeout to max so it doesnt go to sleep during import
it can take a minute

testet with an unholy amount of entrys

Notice, because youtubes JSON does not include duration/watchtime i set a placeholder value that should make it watched no matter what.
Priamry use is to use the watched filter 
