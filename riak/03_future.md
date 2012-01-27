!SLIDE
# For more
## [The Riak Fast Track](http://wiki.basho.com/The-Riak-Fast-Track.html)

!SLIDE
## [Riak Handbook](http://riakhandbook.com/)
(for only $29)

!SLIDE code smaller
    @@@ Python
    import riak

    # Connect to Riak.
    client = riak.RiakClient()

    # Choose the bucket to store data in.
    bucket = client.bucket('test')


    # Supply a key to store data under.
    # The ``data`` can be any data Python's ``json`` encoder can handle.
    person = bucket.new('riak_developer_1', data={
        'name': 'John Smith',
        'age': 28,
        'company': 'Mr. Startup!',
    })
    # Save the object to Riak.
    person.store()


!SLIDE
## Question?
### If I'm able to answer

!SLIDE
# That's all
## @sputnikus