# StateHub
A repository for storing chromatin state definition tables to paint the genome with functional annotation

States are represented by a series of two bit values.

NA - This mark is irrelevant to this state

00 - If this mark is present, it should not overlap with this state

01 - If this mark is present, it should overlap with this state

10 - This mark must be present, and must not overlap with this state

11 - This mark must be present, and must not overlap with this state

