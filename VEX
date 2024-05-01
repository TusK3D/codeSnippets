//Generate a detail attribute using a part of a path attrib from prims
int prims = nprimitives(0);
string name = "";
int success;
for(int i =0; i<prims; i++)
{
    name += "*" + split(prim(0, "path", i), "/")[-1];
    name += "*,";
    
}
setdetailattrib(0, "path", name, "set");
