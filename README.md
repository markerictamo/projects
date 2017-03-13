# Specifications
	
### Core
* CRUD functions example
> 
> Debug
> > var_dump($this->db->error); // show errors
> > echo $this->db->query; // show executed query
>
> Function
> > $this->db->updateRecord([array_fields], '<table>', '<conditions>');