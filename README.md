	<pre><code>usage: AddToVOSViewerNetwork.py [-h] -i INPUTNETWORK -o OUTPUTNETWORK -ci CLUSTERINFO -ii ITEMINFO

Add information to a VOSViewer file.

options:
  -h, --help            show this help message and exit
  -i INPUTNETWORK, --inputNetwork INPUTNETWORK
                        Input VOSViewer JSON network file
  -o OUTPUTNETWORK, --outputNetwork OUTPUTNETWORK
                        Output augmented VOSViewer JSON network file
  -ci CLUSTERINFO, --clusterInfo CLUSTERINFO
                        tab-separated txt-file, cluster level information
  -ii ITEMINFO, --itemInfo ITEMINFO
                        tab-separated txt-file. item level information
    </code></pre>
	
	
<pre><code>>python AddToVOSViewerNetwork.py -i ExampleNetwork.json -o ExampleNetworkAugmented.json -ii itemInfo.txt -ci clusterInfo.txt	</code></pre>
