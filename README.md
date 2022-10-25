### Instructions

open oci cloud shell

<p>
git clone https://github.com/mikarinneoracle/atp-ords-liquibase-demo.git

<p>
edit <code>script.sh</code> with oci code editor<br>
=> add your oci compartment by replacing <i><YOUR COMPARTMENT OCID></i> and the region if necessary (lines 1-2):

<p>
<pre>
export region='eu-amsterdam-1'
export compt_ocid='<YOUR COMPARTMENT OCID>'
</pre>

<p>
run sh script.sh

<p>
access <i>pricing bucket</i> from your browser and open the <code>index.html</code>