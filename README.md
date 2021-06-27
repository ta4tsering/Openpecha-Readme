### Contents
    1. README.md
        Path = Pecha_id/README.md
        eg: P000001/README.md
            
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/Readme.png)

    2. meta.yml
        Path = Pecha_id/Pecha_id.opf/meta.yml
        eg: P000001/P000001.opf/meta.yml
            
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/meta.png)

        2.1 different types of initial_creation_type
            2.1.1 ebook
                initial_creation_type = ebook
            2.1.2 ocr
                initial_creation_type = ocr

    3. Pecha_id.opf
        Path = Pecha_id/Pecha_id.opf
        3.1 base
            Path = pecha_id/pecha_id.opf/base/volumenum.txt
            eg: P000001/P000001.opf/base/v001.txt
                
        3.1 layers
            3.1.1 There are two different layers content
                1 layer files of pecha with initial_creation_type = ebook
                   1.1 Author.yml
                   1.2 BookTitle.yml
                   1.3 Chapter.yml
                   1.4 Citation.yml
                   1.5 Tsawa.yml
                   1.6 Quotaion.yml
                   1.7 Yigchung.yml
                   1.8 Sabche.yml

            Path = Pecha_id/Pecha_id.opf/layers/volumenum/filename.yml
            eg: P000010/P000010.opf/layers/v001/Author.yml
                
![](https://raw.githubusercontent.com/ta4tsering/Openpecha-Readme/main/images/ebook_layers.png)
                
                2 layer files of pecha with initial_creation_type = ocr 
                    2.1 Pagination.yml
                        there are two types of Pagination.yml
                        one is updated version with image_group_id and pagination of the pechas
                        other one is without the image_group_id and pagination of the pechas
                        

                            
