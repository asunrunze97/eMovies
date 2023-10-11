# eMovies
project for CSCI381 Data Modeling 

1. init data models
    create eMovies repository on github
    add base data model to eMovies

2. change names to proper case
    use buck editor (Table -> Name&Physical Name -> copy to google sheet -> paste back) 

3. split movie star&dirctor out and make bridge table
    create 3 new enitities and 3 bridge table
    
4. split payment type to 3(card/check/epay)
    create 3 new enitities and used sub-Category

5. change to proper case
    after done 3&4 some name is not in right form

6. in Movie Rental Record replaced SSN with employee number, and delated customer credit table
    delated the old Relationship (Employee Number -- Movie Rental Record)
    rebuild the Relationship with target attribute
    delated customer credit table,  it seems unnecessary becaused we already have payment

7. removed address 2, and only use address type
    in domin editor, replaced all address 2 with address

8. update domin names with proper case
    use buck editor