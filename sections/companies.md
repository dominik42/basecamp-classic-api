Companies
=========

Get companies
-------------

* `GET /companies.xml` returns a list of all companies visible to the requesting user.
* `GET /projects/#{project_id}/companies.xml` returns a list of all companies associated with the given project.

**Response:**

    <companies>
      <company>
        ...
      </company>
      <company>
        ...
      </company>
      ...
    </company>


Get company
-----------

* `GET /companies/#{company_id}.xml` returns a single company identified by its integer ID.

**Response:**

    <company>
      <id type="integer">1</id>
      <name>Globex Corporation</name>
    </company>