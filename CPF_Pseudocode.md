# CPF Pseudocode

state = PersonalityVector()

def interpret(input):
    emotional = EmotionalGradient(input)
    relation  = RelationalGravity(input, state)
    moral     = DynamicMoralWeight(context)
    update(state, emotional, relation)
    return combined(emotional, relation, moral)
