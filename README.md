For a 'getting started' guide and sample project, go to http://www.throwthelookingglass.com/2011/06/box2fp-tutorial-making-games-with-flashpunk-and-box2d/

__Note__: This is a fork of pdyxs' work. Fixed some bugs and added a few features.
A modified version of Box2DFlash 2.1alpha is included (with mem bugfixes found on forums and other changes).

Changelog:
- added PreRotation to SuperGraphiclist 
- b2Vec2 are now chainable (making working with them a lot easier)
- added easy to use debug property in Box2DWorld
- added b2Body.Destroy()
- modified b2Fixture.Destroy(), b2ContactFactory.Destroy(), b2World.DestroyBody()
- modified Box2DEntity.update() (partial fix for Body position)
