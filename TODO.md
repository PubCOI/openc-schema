## TODO

### companies-schema.json

(not mapping datum, as it appears this is being
 replaced by 'statements')

various issues: outstanding questions below

```
alternate_registration_entities[]
previous_registration_entities[]
subsequent_registration_entities[]
: need examples of child entities

number_of_employees
: currently [string, number, null], is
  it safe to make this number|null only?

branch_status; agent_name; agent_address
: need an example ... gone with string for all
  of these for now

trademark_registrations[]
: need some examples

registered_agent_name -> rename:
: agent_name 

registered_agent_address -> rename
: agent_address

corporate_groupings[]
: ??? examples required

financial_summary??

home_company??  ... should this be a Company entity? or 
just a company number?


**
all entries from 'website' are unknown ..
are they required??
```

officers.json

```
current_status
: example required ... what is this??
```