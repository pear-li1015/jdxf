一个dxf文件包含多个段(DXFSection)
有多种段HEADER、CLASSES、TABLES、BLOCKS、ENTITIES、OBJECTS等



```code
SECTION
    HEADER
ENDSEC
SECTION
    CLASSES
ENDSEC
SECTION
    TABLES
        TABLE
        ENDTAB // 第三多
ENDSEC
SECTION
    BLOCKS
        BLOCK // 第二多
        ENDBLK
ENDSEC
SECTION
    ENTITIES
        AcDbEntity //最多
        
ENDSEC
SECTION
    OBJECTS
        
ENDSEC
```