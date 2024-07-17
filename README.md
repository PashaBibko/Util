# Util

## Summary

Custom Util Library I use for most of my projects
Below is the list of files and thier contents

## Files

1. Util.h
> Includes all files within this library
> It is not needed to be used as all files will compile on thier own

2. Vec2.h
> Includes a templated Vec2 class
> Only accepts arethmetic types as the contents
> Has typenames for:
> Int - Vec2i
> Unsigned Int - Vec2u
> Float - Vec2f
> Double - Vec2d
> Has most operator overloads including converting one vector to another
> Also overloads the std functions abs, min and max so they are useable with the class
> Has conversion to box2D and SFML vectors if they are included

3. Map-Manip.h
> Contains useful functions for easier map use
> All functions are inline to get rid of any overhead
> If you only use one of std::map and std::unordered_map you can change which ones will be compiled
> Do this by defining the macro: DONT_MAP_MANIP(map type in capitals) to true
