This is version 1.0 of the ConTeXt Greek module for typesetting
ancient (polytonic) Greek in ConTeXt. Copyright (C) 2007 Thomas A. Schmitz.



INSTALLATION

For instructions, see the file greekmodule.pdf. Here is a short version for the
impatient:

- Unzip the file texmf.zip in your local or personal texmf-tree.

- ConTeXt can load mapfiles on demand, and the module is set up to use this
  feature. If you have trouble with fonts not being found, try to update
  your mapfile by running updmap-sys --enable Map tasgreek.map

Unicode input will only work with ConTeXt versions later than
2005-03-16. 



CONTENT

This module contains the following files:

doc
doc/greek
doc/greek/readme.txt (this file)
doc/greek/greekmodule.pdf

fonts
fonts/enc
fonts/enc/dvips
fonts/enc/dvips/greek
fonts/enc/dvips/greek/a_7zngnl.enc
fonts/enc/dvips/greek/agr-GFSD.enc
fonts/enc/dvips/greek/agr.enc
fonts/enc/dvips/greek/agralk.enc
fonts/enc/dvips/greek/agrlalk.enc
fonts/enc/dvips/greek/aisagr.enc
fonts/enc/dvips/greek/ariagr.enc
fonts/enc/dvips/greek/artagr.enc
fonts/enc/dvips/greek/artitagr.enc
fonts/enc/dvips/greek/astagr.enc
fonts/enc/dvips/greek/astboagr.enc
fonts/enc/dvips/greek/astitagr.enc
fonts/enc/dvips/greek/bodagr.enc
fonts/enc/dvips/greek/bodboagr.enc
fonts/enc/dvips/greek/bodoclasagr.enc
fonts/enc/dvips/greek/canagr.enc
fonts/enc/dvips/greek/canagrit.enc
fonts/enc/dvips/greek/caragr.enc
fonts/enc/dvips/greek/CB.enc
fonts/enc/dvips/greek/centagr.enc
fonts/enc/dvips/greek/dioboagr.enc
fonts/enc/dvips/greek/dioitagr.enc
fonts/enc/dvips/greek/dioxagr.enc
fonts/enc/dvips/greek/elpisagr.enc
fonts/enc/dvips/greek/elpisagr.enc~
fonts/enc/dvips/greek/freeagr.enc
fonts/enc/dvips/greek/freeagrit.enc
fonts/enc/dvips/greek/gandagr.enc
fonts/enc/dvips/greek/garagr.enc
fonts/enc/dvips/greek/gdragr.enc
fonts/enc/dvips/greek/genagr.enc
fonts/enc/dvips/greek/genaltagr.enc
fonts/enc/dvips/greek/genaltlunagr.enc
fonts/enc/dvips/greek/genlunagr.enc
fonts/enc/dvips/greek/gentagr.enc
fonts/enc/dvips/greek/gmtr.enc
fonts/enc/dvips/greek/grbagr.enc
fonts/enc/dvips/greek/ibyagr.enc
fonts/enc/dvips/greek/ibyagr.enc~
fonts/enc/dvips/greek/ibybagr.enc
fonts/enc/dvips/greek/ibyblagr.enc
fonts/enc/dvips/greek/ibyblagr.enc~
fonts/enc/dvips/greek/ibylagr.enc
fonts/enc/dvips/greek/ibylagr.enc~
fonts/enc/dvips/greek/kadmagr.enc
fonts/enc/dvips/greek/kerkagr.enc
fonts/enc/dvips/greek/koragr.enc
fonts/enc/dvips/greek/korlagr.enc
fonts/enc/dvips/greek/minagr.enc
fonts/enc/dvips/greek/mincagr.enc
fonts/enc/dvips/greek/monagr.enc
fonts/enc/dvips/greek/monagr.enc~
fonts/enc/dvips/greek/nealtagr.enc
fonts/enc/dvips/greek/neoagr.enc
fonts/enc/dvips/greek/neoagr.enc~
fonts/enc/dvips/greek/olgagr.enc
fonts/enc/dvips/greek/oxolagr.enc
fonts/enc/dvips/greek/oxonagr.enc
fonts/enc/dvips/greek/palagr.enc
fonts/enc/dvips/greek/porsagr.enc
fonts/enc/dvips/greek/porsagr.enc~
fonts/enc/dvips/greek/theoagr.enc
fonts/enc/dvips/greek/timagr.enc
fonts/enc/dvips/greek/vusagr.enc

fonts/map
fonts/map/pdftex
fonts/map/pdftex/context
fonts/map/pdftex/context/tasgreek.map

fonts/opentype
fonts/opentype/greek
fonts/opentype/greek/gfsartemis
fonts/opentype/greek/gfsartemis/GFSArtemisia.otf
fonts/opentype/greek/gfsartemis/GFSArtemisiaBold.otf
fonts/opentype/greek/gfsartemis/GFSArtemisiaBoldItalic.otf
fonts/opentype/greek/gfsartemis/GFSArtemisiaItalic.otf
fonts/opentype/greek/gfsbodoniclassic
fonts/opentype/greek/gfsbodoniclassic/GFSBodoniClassic.otf
fonts/opentype/greek/gfsdidot
fonts/opentype/greek/gfsdidot/GFSDidot.otf
fonts/opentype/greek/gfsdidot/GFSDidotBold.otf
fonts/opentype/greek/gfsdidot/GFSDidotBoldItalic.otf
fonts/opentype/greek/gfsdidot/GFSDidotItalic.otf
fonts/opentype/greek/gfselpis
fonts/opentype/greek/gfselpis/GFSElpis.otf
fonts/opentype/greek/gfsneohellenic
fonts/opentype/greek/gfsneohellenic/GFSNeohellenic.otf
fonts/opentype/greek/gfsneohellenic/GFSNeohellenicBold.otf
fonts/opentype/greek/gfsneohellenic/GFSNeohellenicBoldItalic.otf
fonts/opentype/greek/gfsneohellenic/GFSNeohellenicItalic.otf
fonts/opentype/greek/gfsolga
fonts/opentype/greek/gfsolga/GFSOlga.otf
fonts/opentype/greek/gfsporson
fonts/opentype/greek/gfsporson/GFSPorson.otf
fonts/opentype/greek/gfstheokritos
fonts/opentype/greek/gfstheokritos/GFSTheokritos.otf

fonts/tfm
fonts/tfm/greek
fonts/tfm/greek/aisa
fonts/tfm/greek/aisa/aisagr-AisaUC.tfm
fonts/tfm/greek/aisa/aisagr-AisaUCb.tfm
fonts/tfm/greek/aisa/aisagr-AisaUCbi.tfm
fonts/tfm/greek/aisa/aisagr-AisaUCi.tfm
fonts/tfm/greek/aisa/aisagr-raw-AisaUC.tfm
fonts/tfm/greek/aisa/aisagr-raw-AisaUCb.tfm
fonts/tfm/greek/aisa/aisagr-raw-AisaUCbi.tfm
fonts/tfm/greek/aisa/aisagr-raw-AisaUCi.tfm
fonts/tfm/greek/alkaios
fonts/tfm/greek/alkaios/agralk-Alkaios.tfm
fonts/tfm/greek/alkaios/agrlalk-Alkaios.tfm
fonts/tfm/greek/aristarcoj
fonts/tfm/greek/aristarcoj/ariagr-Aristarcoj.tfm
fonts/tfm/greek/aristarcoj/ariagr-raw-Aristarcoj.tfm
fonts/tfm/greek/aristarcoj/Aristarcoj.tfm
fonts/tfm/greek/asteria
fonts/tfm/greek/asteria/GreekAsteria.tfm
fonts/tfm/greek/asteria/GreekAsteriabo.tfm
fonts/tfm/greek/asteria/GreekAsteriaBoldraw.tfm
fonts/tfm/greek/asteria/GreekAsteriait.tfm
fonts/tfm/greek/asteria/GreekAsteriaItalicraw.tfm
fonts/tfm/greek/asteria/GreekAsteriaraw.tfm
fonts/tfm/greek/bosporos
fonts/tfm/greek/bosporos/bosnew.tfm
fonts/tfm/greek/bosporos/Bosporosc.tfm
fonts/tfm/greek/bosporos/Bosporosl.tfm
fonts/tfm/greek/canon
fonts/tfm/greek/canon/canagr-MgOpenCanonica.tfm
fonts/tfm/greek/canon/canagr-MgOpenCanonicaBold.tfm
fonts/tfm/greek/canon/canagr-MgOpenCanonicaBoldItalic.tfm
fonts/tfm/greek/canon/canagrit-MgOpenCanonica-Italic.tfm
fonts/tfm/greek/cardo
fonts/tfm/greek/cardo/caragr-Cardo98s.tfm
fonts/tfm/greek/cardo/caragr-l-Cardo98s.tfm
fonts/tfm/greek/cardo/caragr-raw-Cardo98s.tfm
fonts/tfm/greek/cardo/Cardo.tfm
fonts/tfm/greek/cardo/Cardos.tfm
fonts/tfm/greek/dioxipe
fonts/tfm/greek/dioxipe/dioboagr-Dioxipe-Bold.tfm
fonts/tfm/greek/dioxipe/dioboagr-raw-Dioxipe-Bold.tfm
fonts/tfm/greek/dioxipe/dioitagr-Dioxipe-Italic.tfm
fonts/tfm/greek/dioxipe/dioitagr-raw-Dioxipe-Italic.tfm
fonts/tfm/greek/dioxipe/dioxagr-dioxi.tfm
fonts/tfm/greek/dioxipe/dioxagr-l-dioxi.tfm
fonts/tfm/greek/dioxipe/dioxagr-raw-dioxi.tfm
fonts/tfm/greek/dioxipe/dioxagr-raw-Dioxipe.tfm
fonts/tfm/greek/freeserif
fonts/tfm/greek/freeserif/freeagr-FreeSerif.tfm
fonts/tfm/greek/freeserif/freeagrit-FreeSerifBold.afm.tfm
fonts/tfm/greek/freeserif/freeagrit-FreeSerifBold.tfm
fonts/tfm/greek/freeserif/freeagrit-FreeSerifBoldItalic.afm.tfm
fonts/tfm/greek/freeserif/freeagrit-FreeSerifBoldItalic.tfm
fonts/tfm/greek/freeserif/freeagrit-FreeSerifItalic.afm.tfm
fonts/tfm/greek/freeserif/freeagrit-FreeSerifItalic.tfm
fonts/tfm/greek/gandh
fonts/tfm/greek/gandh/gandhai.tfm
fonts/tfm/greek/gandh/gandhar.tfm
fonts/tfm/greek/garamondprem
fonts/tfm/greek/garamondprem/garagr-KERN-GaramondPremrPro-Bd.tfm
fonts/tfm/greek/garamondprem/garagr-KERN-GaramondPremrPro-BdIt.tfm
fonts/tfm/greek/garamondprem/garagr-KERN-GaramondPremrPro-It.tfm
fonts/tfm/greek/garamondprem/garagr-KERN-GaramondPremrPro.tfm
fonts/tfm/greek/gdr
fonts/tfm/greek/gdr/gdr.tfm
fonts/tfm/greek/gentium
fonts/tfm/greek/gentium/Gentium.tfm
fonts/tfm/greek/gentium/GentiumAlt.tfm
fonts/tfm/greek/gentium/GreekGentium.tfm
fonts/tfm/greek/gentium/GreekGentiumAlt.tfm
fonts/tfm/greek/gentium/GreekGentiumAltItalic.tfm
fonts/tfm/greek/gentium/GreekGentiumAltItaliclun.tfm
fonts/tfm/greek/gentium/GreekGentiumAltlun.tfm
fonts/tfm/greek/gentium/GreekGentiumItalic.tfm
fonts/tfm/greek/gentium/GreekGentiumItaliclun.tfm
fonts/tfm/greek/gentium/GreekGentiumlun.tfm
fonts/tfm/greek/gfsartemis
fonts/tfm/greek/gfsartemis/GFSArtemisia.afm.tfm
fonts/tfm/greek/gfsartemis/GFSArtemisia.tfm
fonts/tfm/greek/gfsartemis/GFSArtemisiabo.tfm
fonts/tfm/greek/gfsartemis/GFSArtemisiaboit.tfm
fonts/tfm/greek/gfsartemis/GFSArtemisiait.tfm
fonts/tfm/greek/gfsbodoni
fonts/tfm/greek/gfsbodoni/gfsgreekbodoni.tfm
fonts/tfm/greek/gfsbodoni/gfsgreekbodonibold.tfm
fonts/tfm/greek/gfsbodoni/gfsgreekbodoniitalic.tfm
fonts/tfm/greek/gfsbodoniclassic
fonts/tfm/greek/gfsbodoniclassic/GFSBodoniClassic.tfm
fonts/tfm/greek/gfsdidot
fonts/tfm/greek/gfsdidot/gfsgreekdidot.tfm
fonts/tfm/greek/gfsdidot/gfsgreekdidotbold.tfm
fonts/tfm/greek/gfsdidot/gfsgreekdidotbolditalic.tfm
fonts/tfm/greek/gfsdidot/gfsgreekdidotitalic.tfm
fonts/tfm/greek/gfselpis
fonts/tfm/greek/gfselpis/GFSElpis.tfm
fonts/tfm/greek/gfsneohellenic
fonts/tfm/greek/gfsneohellenic/GFSNeohellenic.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicalt.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicaltbo.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicaltboit.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicaltit.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicbo.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicboit.tfm
fonts/tfm/greek/gfsneohellenic/GFSNeohellenicit.tfm
fonts/tfm/greek/gfsolga
fonts/tfm/greek/gfsolga/olgagr-GFSOlga.tfm
fonts/tfm/greek/gfsporson
fonts/tfm/greek/gfsporson/GFSPorson.tfm
fonts/tfm/greek/gfstheokritos
fonts/tfm/greek/gfstheokritos/GFSTheokritos.tfm
fonts/tfm/greek/greekcentury
fonts/tfm/greek/greekcentury/greekcentury.tfm
fonts/tfm/greek/greekgaramond
fonts/tfm/greek/greekgaramond/greekgara.tfm
fonts/tfm/greek/greeklfb
fonts/tfm/greek/greeklfb/greeklfb.tfm
fonts/tfm/greek/greekporson
fonts/tfm/greek/greekporson/GreekPorson--base.tfm
fonts/tfm/greek/greekporson/GreekPorson.tfm
fonts/tfm/greek/greekporson/GreekPorsonbo--base.tfm
fonts/tfm/greek/greekporson/GreekPorsonbo.tfm
fonts/tfm/greek/greekporson/GreekPorsonlun.tfm
fonts/tfm/greek/greekporson/GreekPorsonlunbo.tfm
fonts/tfm/greek/greeksang
fonts/tfm/greek/greeksang/Greeksangtf.tfm
fonts/tfm/greek/ibycus
fonts/tfm/greek/ibycus/Ibycus.tfm
fonts/tfm/greek/ibycus/Ibycusbo.tfm
fonts/tfm/greek/ibycus/Ibycusboit.tfm
fonts/tfm/greek/ibycus/Ibycusit.tfm
fonts/tfm/greek/ibycus/Ibycuslun.tfm
fonts/tfm/greek/ibycus/Ibycuslunbo.tfm
fonts/tfm/greek/ibycus/Ibycuslunboit.tfm
fonts/tfm/greek/ibycus/Ibycuslunit.tfm
fonts/tfm/greek/kadmos
fonts/tfm/greek/kadmos/kadmnew.tfm
fonts/tfm/greek/kadmos/kadmo.tfm
fonts/tfm/greek/kadmos/kadmoc.tfm
fonts/tfm/greek/kerkis
fonts/tfm/greek/kerkis/Kerkis-Bold.tfm
fonts/tfm/greek/kerkis/Kerkis-BoldItalic.tfm
fonts/tfm/greek/kerkis/Kerkis-Italic.tfm
fonts/tfm/greek/kerkis/Kerkis.tfm
fonts/tfm/greek/leipzig
fonts/tfm/greek/leipzig/gmtr.tfm
fonts/tfm/greek/leipzig/gmtr1000.tfm
fonts/tfm/greek/leipzig/grbl.tfm
fonts/tfm/greek/leipzig/grbl1000.tfm
fonts/tfm/greek/leipzig/grblnew.tfm
fonts/tfm/greek/leipzig/Leipzig.tfm
fonts/tfm/greek/minion
fonts/tfm/greek/minion/minagr-l-MinionPro-Bold.tfm
fonts/tfm/greek/minion/minagr-l-MinionPro-BoldIt.tfm
fonts/tfm/greek/minion/minagr-l-MinionPro-It.tfm
fonts/tfm/greek/minion/minagr-l-MinionPro-Regular.tfm
fonts/tfm/greek/minion/minagr-MinionPro-Bold.tfm
fonts/tfm/greek/minion/minagr-MinionPro-BoldIt.tfm
fonts/tfm/greek/minion/minagr-MinionPro-It.tfm
fonts/tfm/greek/minion/minagr-MinionPro-Regular.tfm
fonts/tfm/greek/newhellenic
fonts/tfm/greek/newhellenic/NewHellenic--base.tfm
fonts/tfm/greek/newhellenic/NewHellenic.tfm
fonts/tfm/greek/newhellenic/NewHelleniclun.tfm
fonts/tfm/greek/palatino
fonts/tfm/greek/palatino/palagr-PalatinoLinotype-Bold.tfm
fonts/tfm/greek/palatino/palagr-PalatinoLinotype-BoldItalic.tfm
fonts/tfm/greek/palatino/palagr-PalatinoLinotype-Italic.tfm
fonts/tfm/greek/palatino/palagr-PalatinoLinotype-Roman.tfm
fonts/tfm/greek/palatino/PalatinoLinotype-Roman.tfm
fonts/tfm/greek/teubner
fonts/tfm/greek/teubner/Teubnerc.tfm
fonts/tfm/greek/times
fonts/tfm/greek/times/timagr-Times-Bold.tfm
fonts/tfm/greek/times/timagr-Times-BoldItalic.tfm
fonts/tfm/greek/times/timagr-Times-Italic.tfm
fonts/tfm/greek/times/timagr-Times-Roman.tfm
fonts/tfm/greek/vusillus
fonts/tfm/greek/vusillus/vusagr-raw-vusilli.tfm
fonts/tfm/greek/vusillus/vusagr-vusilli.tfm

fonts/truetype
fonts/truetype/greek
fonts/truetype/greek/canon
fonts/truetype/greek/canon/MgOpenCanonica-Italic.ttf
fonts/truetype/greek/canon/MgOpenCanonica.ttf
fonts/truetype/greek/canon/MgOpenCanonicaBold.ttf
fonts/truetype/greek/canon/MgOpenCanonicaBoldItalic.ttf
fonts/truetype/greek/canon/MgOpenCanonicaRegular.ttf
fonts/truetype/greek/freeserif
fonts/truetype/greek/freeserif/FreeSerif.ttf
fonts/truetype/greek/freeserif/FreeSerifBold.ttf
fonts/truetype/greek/freeserif/FreeSerifBoldItalic.ttf
fonts/truetype/greek/freeserif/FreeSerifItalic.ttf
fonts/truetype/greek/gentium
fonts/truetype/greek/gentium/GenAI102.TTF
fonts/truetype/greek/gentium/GenAR102.TTF
fonts/truetype/greek/gentium/GenI102.TTF
fonts/truetype/greek/gentium/GenR102.TTF

fonts/type1
fonts/type1/greek
fonts/type1/greek/ibycus
fonts/type1/greek/ibycus/fibb84.pfb
fonts/type1/greek/ibycus/fibr84.pfb
fonts/type1/greek/ibycus/IbycusHTG-Regular.pfb
fonts/type1/greek/kerkis
fonts/type1/greek/kerkis/Kerkis-Bold.pfb
fonts/type1/greek/kerkis/Kerkis-BoldItalic.pfb
fonts/type1/greek/kerkis/Kerkis-Italic.pfb
fonts/type1/greek/kerkis/Kerkis.pfb
fonts/type1/greek/leipzig
fonts/type1/greek/leipzig/grbl1000.pfb
fonts/type1/greek/leipzig/grbl1200.pfb
fonts/type1/greek/lfb
fonts/type1/greek/lfb/lfb10.pfb
fonts/type1/greek/teubner
fonts/type1/greek/teubner/bgbt.pfb
fonts/type1/greek/teubner/Teubner.pfb

fonts/vf
fonts/vf/greek/
fonts/vf/greek/aisa
fonts/vf/greek/aisa/aisagr-AisaUC.vf
fonts/vf/greek/aisa/aisagr-AisaUCb.vf
fonts/vf/greek/aisa/aisagr-AisaUCbi.vf
fonts/vf/greek/aisa/aisagr-AisaUCi.vf
fonts/vf/greek/asteria
fonts/vf/greek/asteria/GreekAsteria.vf
fonts/vf/greek/asteria/GreekAsteriabo.vf
fonts/vf/greek/asteria/GreekAsteriait.vf
fonts/vf/greek/bosporos
fonts/vf/greek/bosporos/Bosporosl.vf
fonts/vf/greek/canon
fonts/vf/greek/cardo
fonts/vf/greek/cardo/caragr-Cardo98s.vf
fonts/vf/greek/cardo/caragr-l-Cardo98s.vf
fonts/vf/greek/dioxipe
fonts/vf/greek/dioxipe/dioxagr-l-dioxi.vf
fonts/vf/greek/gfsdidot
fonts/vf/greek/greekporson
fonts/vf/greek/greekporson/GreekPorson.vf
fonts/vf/greek/greekporson/GreekPorsonbo.vf
fonts/vf/greek/greekporson/GreekPorsonlun.vf
fonts/vf/greek/greekporson/GreekPorsonlunbo.vf
fonts/vf/greek/kadmos
fonts/vf/greek/kadmos/kadmoc.vf
fonts/vf/greek/leipzig
fonts/vf/greek/leipzig/Leipzig.vf
fonts/vf/greek/newhellenic
fonts/vf/greek/newhellenic/NewHellenic.vf
fonts/vf/greek/newhellenic/NewHelleniclun.vf
fonts/vf/greek/oxonia
fonts/vf/greek/oxonia/oxoniac.vf
fonts/vf/greek/oxoniensis
fonts/vf/greek/oxoniensis/GreekOxoniensis.vf
fonts/vf/greek/oxoniensis/GreekOxoniensislun.vf
fonts/vf/greek/vusillus
fonts/vf/greek/vusillus/vusagr-vusilli.vf



MAINTAINER

Please send bug|-|reports, praise, checks to thomas.schmitz at uni-bonn.de
I can't promise I will fix things immediately, but I'll try my best.



LICENSE

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 2 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program; if not, write to the Free Software Foundation, Inc., 59 Temple
Place, Suite 330, Boston, MA 02111-1307 USA



