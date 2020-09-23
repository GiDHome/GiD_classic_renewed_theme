cp /tmp/new_icons/32/document-new.png new.png
cp /tmp/new_icons/32/document-open.png openFile.png
cp /tmp/new_icons/32/document-print.png print.png
cp /tmp/new_icons/32/document-save.png save.png
cp /tmp/new_icons/32/document-save-as.png saveas.png
cp /tmp/new_icons/32/document-multiple.png openMultiple.png
cp /tmp/new_icons/32/document-revert.png reload.png
cp /tmp/new_icons/32/document.png file.png
cp /tmp/new_icons/32/edit-delete.png erase-cross.png
cp /tmp/new_icons/32/folder-pictures.png camera.png
cp /tmp/new_icons/32/folder-new.png newfolder.png
cp /tmp/new_icons/32/go-up.png upfolder.png
cp /tmp/new_icons/32/go-home.png home.png
cp /tmp/new_icons/32/preferences-other.png prefs.png
cp /tmp/new_icons/32/zoom-in.png zoomin.png
cp /tmp/new_icons/32/zoom-out.png zoomout.png
cp /tmp/new_icons/32/zoom-next.png viewnext.png
cp /tmp/new_icons/32/zoom-previous.png viewprev.png
cp /tmp/new_icons/32/zoom-select.png viewlist.png
cp /tmp/new_icons/32/zoom-fit-best.png zframe.png
cp /tmp/new_icons/32/edit-copy.png copy.png
cp /tmp/new_icons/32/help-browser.png help.png
cp /tmp/new_icons/32/view-refresh.png redraw.png
cp /tmp/new_icons/32/application-exit.png exit.png
cp /tmp/new_icons/32/format-list-unordered.png list.png
cp /tmp/new_icons/32/document-open-folder.png folder.png
cp /tmp/new_icons/32/media-playback-start.png play.png
cp /tmp/new_icons/32/media-playback-stop.png stop.png
cp /tmp/new_icons/32/media-playback-pause.png pause.png
cp /tmp/new_icons/32/media-seek-backward.png rewind.png
cp /tmp/new_icons/32/media-skip-forward.png skipforward.png
cp /tmp/new_icons/32/drive-harddisk.png disk.png
echo convert original.png -adaptive-resize 64x64 new.png
echo layer icon from http://www.iconarchive.com/show/small-n-flat-icons-by-paomedia/layers-icon.html 1238  scp Barcelona_fullmodel_16m_20M_ascii.pts.gz Barcelona_fullmodel_8m_100M_ascii.pts.gz miguel@altillo:/home/miguel/GID-git/SearchLab/cases/big/
echo 3D icon from https://www.flaticon.com/free-icon/3d-movie-symbol-for-interface_49235
PostBarContourFill.png icon from https://icons8.com/icon/35175/rainbow
echo Macro.png from https://www.flaticon.com/free-icon/magic-wand_148786#term=magic%20wand&page=1&position=3
echo hourglass.png from https://icon-icons.com/es/icono/historia-reloj/828#32
echo QuestionWindow.png from http://www.iconarchive.com/show/blue-bits-icons-by-icojam/question-faq-icon.html

 1058  cp -p oxygen/16x16/actions/edit-cut.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/docut.png 
 1059  cp -p oxygen/22x22/actions/edit-cut.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_24/docut.png 
 1060  cp -p oxygen/32x32/actions/edit-cut.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/docut.png 
 1061  convert oxygen/48x48/actions/edit-cut.png -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/docut.png 

cp -p elementary-xfce/actions/32/edit-copy.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/copy_text.png
cp -p elementary-xfce/actions/32/edit-cut.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/cut_text.png 
cp -p elementary-xfce/actions/32/edit-paste.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/paste_text.png 
 1093  cp -p elementary-xfce/actions/16/edit-find.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/search.png 
 1094  cp -p elementary-xfce/actions/24/edit-find.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_24/search.png 
 1095  cp -p elementary-xfce/actions/32/edit-find.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/search.png 
 1096  convert elementary-xfce/actions/48/edit-find.png -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/search.png 
 1097  eog elementary-xfce/actions/32/edit-*
 1098  cp -p elementary-xfce/actions/16/edit-redo.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/redo.png 
 1099  cp -p elementary-xfce/actions/16/edit-undo.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/undo.png 
 1100  cp -p elementary-xfce/actions/24/edit-redo.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_24/redo.png 
 1101  cp -p elementary-xfce/actions/32/edit-redo.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/redo.png 
 1102  cp -p elementary-xfce/actions/32/edit-undo.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/undo.png 
 1103  cp -p elementary-xfce/actions/24/edit-undo.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_24/undo.png 
 1104  convert elementary-xfce/actions/48/edit-redo.png -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/redo.png 
 1105  convert elementary-xfce/actions/48/edit-undo.png -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/undo.png 
 1106  find elementary-xfce -name "*date*png" -print|grep 32
 1107  eog `find elementary-xfce -name "*date*png" -print|grep 32`
 1108  cp -p elementary-xfce/apps/16/date.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/date.png 
 1109  cp -p elementary-xfce/apps/32/date.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/date.png 
 1110  cp -p elementary-xfce/apps/24/date.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_24/date.png 
 1111  cp -p elementary-xfce/apps/64/date.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/date.png 

 2102  cp 16x16/actions/document-edit.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/edit_file.png 
 2106  cp 16x16/actions/edit-rename.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/rename.png 
 2120  cp ./16x16/actions/story-editor.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/
 2234  cp 16/media-record.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/Record.png 
 2235  cp 16/media-playback-stop.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/EndRecord.png 
cp -p oxygen/32x32/actions/help-contextual.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/questionarrow.png
cp -p oxygen/32x32/actions/align-horizontal-left.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/align_text_left.png

cp -p oxygen/32x32/actions/go-bottom.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowBottom.png
cp -p oxygen/32x32/actions/go-down.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowDown.png
cp -p oxygen/32x32/actions/go-previous.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowLeft.png
cp -p oxygen/32x32/actions/go-next.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowRight.png
cp -p oxygen/32x32/actions/go-top.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowTop.png
cp -p oxygen/32x32/actions/go-up.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowUp.png
# needs gimp to rotate images:
cp -p oxygen/32x32/actions/go-up.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowUpLeft.png
cp -p oxygen/32x32/actions/go-up.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowUpRight.png
cp -p oxygen/32x32/actions/go-down.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowDownLeft.png
cp -p oxygen/32x32/actions/go-down.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/ArrowDownRight.png

cp -p oxygen/16x16/actions/dialog-close.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/close17.png
cp -p oxygen/32x32/status/dialog-error.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/ErrorWindow.png 
cp -p oxygen/32x32/status/dialog-warning.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/WarningWindow.png 
cp -p oxygen/32x32/status/dialog-information.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/InfoWindow.png

convert oxygen/128x128/actions/go-bottom.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowBottom.png
convert oxygen/128x128/actions/go-down.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowDown.png
convert oxygen/128x128/actions/go-previous.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowLeft.png
convert oxygen/128x128/actions/go-next.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowRight.png
convert oxygen/128x128/actions/go-top.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowTop.png
convert oxygen/128x128/actions/go-up.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowUp.png
convert oxygen/128x128/actions/go-up.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowUpLeft.png
convert oxygen/128x128/actions/go-up.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowUpRight.png
convert oxygen/128x128/actions/go-down.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowDownLeft.png
convert oxygen/128x128/actions/go-down.png  -adaptive-resize 64x64 ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/ArrowDownRight.png

 # ./oxygen/32x32/mimetypes/application-x-executable.png
cp -p elementary-xfce/actions/24/gtk-execute.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/calc.png
cp -p elementary-xfce/actions/16/gtk-execute.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_24/calc.png
cp -p elementary-xfce/actions/64/gtk-execute.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_64/calc.png
cp -p elementary-xfce/actions/32/gtk-execute.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/calc.png

cp -p oxygen/16x16/status/object-locked.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/lock_on.png
# requires modification:
cp -p oxygen/16x16/status/object-unlocked.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_16/lock_off.png
cp -p oxygen/32x32/status/object-locked.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/lock_on.png
cp -p oxygen/32x32/status/object-unlocked.png ~/GID-git/gidproject/themes/GiD_classic_renewed/images/size_32/lock_off.png

for ff in *png; do echo $ff;convert $ff -adaptive-resize 64x64 ../size64/$ff; done
# from 24 to 32 pix: x2.66666666
#  4 --> 6
# 18 --> 24
# 61 --> 81
# 42 --> 56
#  8 --> 12
convert blank_horizontal.png -adaptive-resize 32x6 ../size_32/blank_horizontal.png	    
convert blank_vertical.png  -adaptive-resize 6x32  ../size_32/blank_vertical.png	    
convert GiDdirectory_h.png  -adaptive-resize 32x24 ../size_32/GiDdirectory_h.png	    
convert GiDdirectory.png -adaptive-resize 32x24	   ../size_32/GiDdirectory.png	    
convert info_gid_a.png  -adaptive-resize 81x32	   ../size_32/info_gid_a.png	    
convert info_gid.png  -adaptive-resize 81x32	   ../size_32/info_gid.png		    
convert info_gid_p.png  -adaptive-resize 81x32	   ../size_32/info_gid_p.png	    
convert info_gid_t.png  -adaptive-resize 81x32	   ../size_32/info_gid_t.png	    
convert post_pre.png  -adaptive-resize 56x32	   ../size_32/post_pre.png		    
convert pre_post.png  -adaptive-resize 56x32	   ../size_32/pre_post.png		    
convert sep_hori.png  -adaptive-resize 32x12	   ../size_32/sep_hori.png		    
convert sep_vert.png  -adaptive-resize 12x32	   ../size_32/sep_vert.png
# from 24 to 64 pix: x1.333333
#  4 --> 12
# 18 --> 48
# 61 --> 163
# 42 --> 112
#  8 --> 22
convert blank_horizontal.png -adaptive-resize 64x12 ../size_64/blank_horizontal.png	    
convert blank_vertical.png  -adaptive-resize 12x64  ../size_64/blank_vertical.png	    
convert GiDdirectory_h.png  -adaptive-resize 64x48  ../size_64/GiDdirectory_h.png	    
convert GiDdirectory.png -adaptive-resize 64x48	    ../size_64/GiDdirectory.png	    
convert info_gid_a.png  -adaptive-resize 163x64	    ../size_64/info_gid_a.png	    
convert info_gid.png  -adaptive-resize 163x64	    ../size_64/info_gid.png		    
convert info_gid_p.png  -adaptive-resize 163x64	    ../size_64/info_gid_p.png	    
convert info_gid_t.png  -adaptive-resize 163x64	    ../size_64/info_gid_t.png	    
convert post_pre.png  -adaptive-resize 112x64	    ../size_64/post_pre.png		    
convert pre_post.png  -adaptive-resize 112x64	    ../size_64/pre_post.png		    
convert sep_hori.png  -adaptive-resize 64x22	    ../size_64/sep_hori.png		    
convert sep_vert.png  -adaptive-resize 22x64	    ../size_64/sep_vert.png

git clone https://github.com/pasnox/oxygen-icons-png.git
convert size_64/logout.png -fx '(r+g+b)/3'  size_64/login.png

cp -p /usr/share/icons/oxygen/64x64/places/user-desktop.png size_64/desktop.png
cp -p /usr/share/icons/oxygen/32x32/places/user-desktop.png size_32/desktop.png
cp -p /usr/share/icons/oxygen/16x16/places/user-desktop.png size_16/desktop.png
cp -p /usr/share/icons/oxygen/22x22/places/user-desktop.png size_24/desktop.png
## gimp to change size 22 --> 24
cp -p /usr/share/icons/elementary-xfce/places/64/folder-documents.png size_64/documents.png
cp -p /usr/share/icons/elementary-xfce/places/32/folder-documents.png size_32/documents.png
cp -p /usr/share/icons/elementary-xfce/places/24/folder-documents.png size_24/documents.png
cp -p /usr/share/icons/elementary-xfce/places/16/folder-documents.png size_16/documents.png
cp -p /usr/share/icons/elementary-xfce/places/16/folder-download.png size_16/downloads.png
cp -p /usr/share/icons/elementary-xfce/places/24/folder-download.png size_24/downloads.png
cp -p /usr/share/icons/elementary-xfce/places/32/folder-download.png size_32/downloads.png
cp -p /usr/share/icons/elementary-xfce/places/64/folder-download.png size_64/downloads.png
cp -p /usr/share/icons/elementary-xfce/places/16/folder-publicshare.png size_16/publicshare.png
cp -p /usr/share/icons/elementary-xfce/places/24/folder-publicshare.png size_24/publicshare.png
cp -p /usr/share/icons/elementary-xfce/places/32/folder-publicshare.png size_32/publicshare.png
cp -p /usr/share/icons/elementary-xfce/places/64/folder-publicshare.png size_64/publicshare.png
cp -p /usr/share/icons/oxygen/16x16/actions/dialog-ok.png size_16/dialog-ok-apply.png 
cp -p /usr/share/icons/oxygen/32x32/actions/dialog-ok.png size_32/dialog-ok-apply.png 
cp -p /usr/share/icons/oxygen/64x64/actions/dialog-ok.png size_64/dialog-ok-apply.png 
cp -p /usr/share/icons/oxygen/22x22/actions/dialog-ok.png size_24/dialog-ok-apply.png 
## gimp to change size 22 --> 24
cp -p /usr/share/icons/oxygen/64x64/categories/applications-system.png size_64/configuration.png
cp -p /usr/share/icons/oxygen/32x32/categories/applications-system.png size_32/configuration.png
cp -p /usr/share/icons/oxygen/16x16/categories/applications-system.png size_16/configuration.png
cp -p /usr/share/icons/oxygen/22x22/categories/applications-system.png size_24/configuration.png
gimp size_24/configuration.png

https://www.flaticon.com/free-icon/bracket_605716?term=bracket&page=1&position=28
cp -p /usr/share/icons/oxygen/16x16/actions/im-user-offline.png images/size_16/login.png
cp -p /usr/share/icons/oxygen/16x16/actions/im-user.png images/size_16/logout.png
cp -p /usr/share/icons/oxygen/24x24/actions/im-user-offline.png images/size_24/login.png
cp -p /usr/share/icons/oxygen/22x22/actions/im-user-offline.png images/size_24/login.png
cp -p /usr/share/icons/oxygen/22x22/actions/im-user.png images/size_24/logout.png
cp -p /usr/share/icons/oxygen/32x32/actions/im-user-offline.png images/size_32/login.png
cp -p /usr/share/icons/oxygen/32x32/actions/im-user.png images/size_32/logout.png
cp -p /usr/share/icons/oxygen/64x64/actions/im-user-offline.png images/size_64/login.png
cp -p /usr/share/icons/oxygen/64x64/actions/im-user.png images/size_64/logout.png

./128x128/categories/applications-education-miscellaneous.png
./16x16/categories/applications-education-miscellaneous.png
./22x22/categories/applications-education-miscellaneous.png
./32x32/categories/applications-education-miscellaneous.png
./48x48/categories/applications-education-miscellaneous.png
./64x64/categories/applications-education-miscellaneous.png
As PostBarShMinMax.png PostBarShMin.png PostBarShMax.png
