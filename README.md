# LuauAstLua
LAL (LuauAstLua) is a code transpilation of the LuaU AST from cpp into vanilla lua

Please note that I am not fluent in cpp, so some things might not behave as they should (mainly with unicode / string manipulation in general).
This code has a few artifacts (mainly TempVector) which I may remove in the near future.
There is no AstVisitor class, but a table with a visit (self, node) function will work.
