# ricoh-theta-batch-stitch-cygwin
Script for batch-stitching Ricoh Theta Dual FishEye files using Cygwin on Windows

This is a shameful copy/paste and adaptation for Windows of http://qiita.com/mizba/items/d3139e81b38ca6d29260 , original copyright goes to mizba
# How to use:

1. Install Cygwin on your computer if you do not already have it.
2. Save this script to the same folder as the one where your MP4 Theta files are
3. Open cygwin, cd into your directory (for instance  cd $(cygpath.exe 'H:\data\photos\100RICOH'))
4. Modify the path to your DualfishBlender.exe (on line 13) file in case you installed it in a non-standard directory.
5. Run the script: ./batch_stitch.sh
