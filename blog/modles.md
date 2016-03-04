In our blog

Features:

    Blog will have the following features:

        1. Post(Table in database)
        2. Categores(Table in database)
        3. Tag(Table in our database)
        4. Author(Table in our database)

    Let us make a relation betwee our tables:

        1. Post can have many catergories, and a categories can have many post
            (Relation between Post and Category table)(ManytoMany Relation)
        2. A tag can have many Post and a Post cam have many Tag (ManytoMany Relation)
        3. Author can have many Posts and a Post can have a single author(OnetoMany Relation)
            [no post can write by more than authors]

    Attributes for tables:

        Post:
            1. title
            2. created_date
            3. body
            4. tags
            5. category
            6. author

        Categories:
            1. cat_name
            2. cat_description

        Author:
            1. author_name
            2. author_email(not mandatory)
            3. author_bio

        Tag:
            1. tag_name