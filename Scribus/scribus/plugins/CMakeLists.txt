ADD_SUBDIRECTORY(barcodegenerator)
ADD_SUBDIRECTORY(colorwheel)
ADD_SUBDIRECTORY(fileloader)
ADD_SUBDIRECTORY(fontpreview)
ADD_SUBDIRECTORY(gettext)
ADD_SUBDIRECTORY(import)
# ADD_SUBDIRECTORY(newfromtemplateplugin)
ADD_SUBDIRECTORY(pixmapexport)
ADD_SUBDIRECTORY(saveastemplateplugin)
IF(NOT WIN32)
  ADD_SUBDIRECTORY(scriptplugin)
ENDIF(NOT WIN32)
ADD_SUBDIRECTORY(short-words)
ADD_SUBDIRECTORY(svgexplugin)
# ADD_SUBDIRECTORY(imposition)
ADD_SUBDIRECTORY(tools)
#ADD_SUBDIRECTORY(picbrowser)

# ADD_SUBDIRECTORY(myplugin)
