Gingerbread for Motorola MB611 (CM 2.3.7)

Download:

repo init -u git://github.com/shldol/android.git -b gingerbread
repo sync

Download RomManager (DELETED BY OUR BUILD SYSTEM)

mkdir -p vendor/cm/proprietary 
cd vendor/cm && ./get-prebuilts

Build:

rm -rf out/target

For CM7 branch : source build/envsetup.sh && brunch begonia

Use the signed zip to update the defy with the bootmenu recovery, not the ota package !