# Sweeney-Ads-Audience-Responses-to-a-Repeated-Sexualised-Campaign-Tactic
{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "8bf85731",
   "metadata": {},
   "source": [
    "# Persist, Fade, or See Through It? Audience Responses to a Repeated Sexualised Ad Tactic\n",
    "\n",
    "\n",
    "**Overarching question.** When the same controversial marketing tactic (here, the sexualised portrayal of a female endorser) is repeated, did audience attitudes toward it change, and if so, how?\n",
    "\n",
    "**Comparison.** American Eagle (AE) *\"Sydney Sweeney Has Great Jeans\"* (launched 23 Jul 2025) vs Novig *\"Just sports\"* (launched 9 Sep 2026). Same endorser, similar tactic; both brands kept working with her. Only **gender-related** comments are compared, because the sexualised portrayal is the one controversy the two ads share.\n",
    "\n",
    "**Research questions.**\n",
    "- **RQ1 (persistence):** Did criticism of the sexualised portrayal persist from the AE to the Novig campaign, and over time within each?\n",
    "- **RQ2 (form):** Did the form of criticism change, toward indifference (T2) or toward recognising the marketing tactic (T3)?\n",
    "- **RQ3 (focus):** What did the discussion focus on, and did that focus change between the two campaigns?\n",
    "\n",
    "**Three competing scenarios (Framework T).**\n",
    "\n",
    "| Level of attitude | T1 Persistence | T2 Desensitisation | T3 Persuasion knowledge | RQ |\n",
    "|---|---|---|---|---|\n",
    "| Tone: negative share and emotional intensity | same | lower | lower | RQ1 |\n",
    "| Stance: share objecting to the portrayal | same or higher | lower | about the same | RQ1 |\n",
    "| Form of criticism | mainly moral condemnation | growing indifference | growing references to the marketing tactic | RQ2 |\n",
    "\n",
    "**Data.** Top-level YouTube comments collected with the YouTube Data API v3 (see `sydeney data collection.py`). Conclusions are stated at the level of public discourse, not individual users."
   ]
  },
  {
   "cell_type": "code",
   "execution_count": null,
   "id": "4c8cc98e",
   "metadata": {
    "execution": {
     "iopub.execute_input": "2026-11-08T02:44:24.945581Z",
     "iopub.status.busy": "2026-11-08T02:44:24.945409Z",
     "iopub.status.idle": "2026-11-08T02:44:26.229605Z",
     "shell.execute_reply": "2026-11-08T02:44:26.228536Z"
    }
   },
   "outputs": [
    {
     "name": "stdout",
     "output_type": "stream",
     "text": [
      "Note: you may need to restart the kernel to use updated packages.\n"
     ]
