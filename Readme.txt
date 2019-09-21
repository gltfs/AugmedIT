Place here your models

Folder structure
-----------------
Create a folder per model
Create under this folder a folder per format and place the associated files there. Example:

	TestmodelHoloMFS
		gltf
			undefined.gltf
		glb
			undefined.glb
		stl
			Hollowish_Skull-Mandible.stl

If you derive formats from a DICOM set, then you can keep them hierarchically together like this:

	Patient 20180404
		DICOM
	      		*.*
	   	Brain
      			stl
         			Brain.stl
	   	Tumor
      			stl
          			tumor.stl
	      		obj
        	 		tumor.obj

File size
----------
Files cannot be larger than 100 MB for git. 
If they are longer, include them in the .gitignore file in the root.