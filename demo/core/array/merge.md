## Array#merge

    require 'facets/array/merge'

    a = [1,2,3]
    b = [3,4,5]
    a.merge(b).assert == [1,2,3,4,5]

## Array#merge!

    a = [1,2,3]
    b = [3,4,5]
    a.merge!(b)
    a.assert == [1,2,3,4,5]

