### Contents
    Openpecha repository file or folders
        1. meta.yml
            Path = Pecha_id/Pecha_id.opf/meta.yml
            eg: P000001/P000001.opf/meta.yml
            
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/meta.png)

            1.1 different types of initial_creation_typ
                1.1.1 ebook
                
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/ebook_layers.png)

                1.1.2 ocr
                
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/initial_ocr.png)

        2. README.md
            Path = Pecha_id/README.md
            eg: P000001/README.md
            
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/Readme.png)

        2. base
            2.1 base files names
                Path = pecha_id/pecha_id.opf/base/volumenum.txt
                eg: P000001/P000001.opf/base/v001.txt
                
        3. layers
            3.1 different types of layer folders
                Path = Pecha_id/Pecha_id.opf/layers/volumenum/filename.yml
                eg: P000010/P000010.opf/layers/v001/Author.yml
                
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/ebook_layers.png)

                3.1.1 layer files of pecha with initial_creation_type = ebook
                    3.1.1.1 Author.yml
                    3.1.1.2 BookTitle.yml
                    3.1.1.3 Chapter.yml
                    3.1.1.4 Citation.yml
                    3.1.1.5 Tsawa.yml
                    3.1.1.6 Quotaion.yml
                    3.1.1.7 Yigchung.yml
                    3.1.1.8 Sabche.yml  
                    
                3.1.2 layer files of pecha with initial_creation_type = ocr 
                    Path = Pecha_id/Pecha_id.opf/layers/volumenum/Pagination.yml
                    eg: P000001/P000001.opf/layers/v001/Pagination.yml
                    
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/pagination.png)

                    3.1.2.1 Pagination.yml
                            there are two types of Pagination.yml
                            one is updated version with image_group_id and pagination of the pechas
                            other one is without the image_group_id and pagination of the pechas
                        

                            
